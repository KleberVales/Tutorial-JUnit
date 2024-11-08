# Tutorial JUnit

1. Introdução ao JUnit:
- O que é o JUnit e por que usá-lo.
- Arquitetura e principais componentes do JUnit.
- Histórico do JUnit (JUnit 3, 4 e 5).
  
2. Estrutura Básica de Testes:
- Criando uma classe de testes no JUnit.
- Anotações principais: @Test, @BeforeEach, @AfterEach, @BeforeAll, @AfterAll.
- Assertivas: assertEquals(), assertNotNull(), assertTrue(), etc.
  
3. Anotações do JUnit 5:
- @Test: Definindo métodos de teste.
- @BeforeEach e @AfterEach: Inicializando e limpando antes e depois de cada teste.
- @BeforeAll e @AfterAll: Inicialização e limpeza de uma vez para toda a classe de teste.
- @Disabled: Desabilitando um teste.
- @ParameterizedTest e @ValueSource: Para testes com parâmetros.
  
4. Testes Parametrizados:
- Como usar o @ParameterizedTest para rodar o mesmo teste com diferentes valores.
- Tipos de fontes de dados: @ValueSource, @EnumSource, @MethodSource.
  
5. Exceções e Erros:
- Testando exceções com assertThrows().
- Verificando mensagens de erro.
  
6. Testes de Performance:
- Como realizar testes de tempo de execução com @Test e medir o tempo com assertTimeout().
  
7. Mocks e Stubs:
- Utilizando frameworks como Mockito para criar mocks e stubs em seus testes JUnit.
- Como testar interações com dependências externas.
  
8. Estratégias de Teste:
- Testes unitários vs Testes de integração.
- Cobertura de código e boas práticas em testes.
- TDD (Test-Driven Development): Como aplicar em seu fluxo de trabalho.
  
9. Execução de Testes e Relatórios:
- Como executar os testes em IDEs como IntelliJ, Eclipse, ou via linha de comando.
- Gerando relatórios de execução de testes.

10. Testando o Código Assíncrono e Concorrente:
- Estratégias para testar código assíncrono e threads usando JUnit.
