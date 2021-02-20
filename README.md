## Set Interface

?
📌 O que é ?

    É uma interface que representa um conjunto de elementos
    
📌 Características ?
    
    .Não admite repetições. ✅
    .Elementos não possuem posição(porem em alguns casos , ordenação).✅
    .Acesso,incersão e remoção de elementos são rápidos.✅
    .Oferece operações eficientes de conjuntos (Inserção,união e diferença).✅
    
 📌 Principais Implementações ?   
 
    . HashSet: Mais rápido (Operações O(1) em tabela Hash) e não possuem ordenação.✅ 
    
      Ex .. Set<String> set = new HashSet<>();
      
    . TreeSet: Mais lento (Operações O(log(n)) em árvore rubro-negro) e ordenado pelo compareTo do objeto ou Comparator.✅ 
    
      Ex .. Set<String> set = new TreeSet<>();
      
    . LinkedHashSet:Velocidade intermediára e elementos na ordem que são adicionados.✅ 
    
      Ex .. Set<String> set = new LinkedHashSet<>();
      
      
  📌 Alguns métodos Implementados ?
  
    . add, remove,contais (Baseado em equals e Hashcode, se não existir, é utilizado a comparação de ponteiros).✅
    . clear();✅
    . size();✅
    . removeIf(predicate) Exemplo ..  removeIf(x->x.charAt(0) == 'T').✅
    . addAll(other) - União , adiciona no conjunto os elementos do 'other' sem repetir.✅
    . retainAll(other) - Intersecção, remove do conjunto os elementos não contidos em 'other'.✅
    . removeAll(other) - Diferença, remove do conjunto os elementos contidos em 'other'✅

    
    




