# Map - [Mapa]

- Definição: 
    - <R> Stream<R> map(Function<? super T,? extends R> mapper)

- Tipo: 
    - Operação Intermediária
    
- Parâmetro:
    - Função

- Retorno:
    - Retorna um fluxo mapeado, ou seja, um fluxo que contém os resultados da aplicação da função fornecida no fluxo original 

- Exemplo: 
    ```
    List<Integer> numeros = Arrays.asList(2, 4, 8, 10);
    List<Integer> raizez_quadradas = numeros.stream().map(x->x*x).toList();
    ```
- Diagrama:

    ![Map](../images/04_map.png)

- Fonte: 
    - https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html