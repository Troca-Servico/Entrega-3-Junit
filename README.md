# Documentação de Testes - Classe CadastroTest 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Teste JUnit para o Salvamento dos dados do usuário.

O propósito deste teste é assegurar a correta funcionalidade do processo de armazenamento de cada informação no banco de dados. Isso envolve a verificação da precisão no salvamento das informações fornecidas pelo usuário, avaliando se os dados foram registrados com sucesso ou não. O resultado do teste será apresentado em termos percentuais, indicando a taxa de sucesso, juntamente com uma descrição do método utilizado.O objetivo deste teste é garantir a funcionalidade correta do processo de salvamento de cada informação no banco de dados. Verificando se as informações cadastradas que o usuário nos informou deram certas ou não. Mostrando a % e o método feito.

A classe CadastroTest contém testes unitários que visam garantir o funcionamento dos métodos da classe Cadastro no projeto de troca de serviços. Abaixo está uma descrição detalhada de cada teste.

 1. Teste de getCpf
    
    ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/caeccb52-c109-4ef8-b0ae-18df6c80148c)

* Descrição: Este teste verifica se o método getCpf da classe Cadastro retorna corretamente o CPF associado à instância.
* Cenário de Teste: Quando o usuario informa o seu CPF para complemetar o seu cadastro, sem o . e -
* Expectativa: O método getCpf deve retornar o CPF esperado.

2. Teste de getDescSer

   ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/2c7d5e62-ef21-4b66-8782-22da2f77c3bf)

* Descrição: Este teste valida se o método getDescSer retorna a descrição do serviço associada à instância.
* Cenário de Teste: Quando o usuario inicializada com uma descrição de serviço específica.
* Expectativa: O método getDescSer deve retornar a descrição de serviço esperada.

3. Teste de getCidade
   
   ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/28013868-cd21-437c-9484-3347182231c4)

* Descrição: Este teste assegura que o método getCidade retorne corretamente a cidade associada à instância.
* Cenário de Teste: Quando o usuario inicializada com uma cidade específica.
* Expectativa: O método getCidade deve retornar a cidade esperada.

4. Teste de getAreasInteresse
   
   ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/3ce6c967-0fd0-4dc5-8ac2-576e093966c6)

* Descrição: Este teste confirma se o método getAreasInteresse retorna as áreas de interesse associadas à instância.
* Cenário de Teste:Qauando o usuario informa com as áreas de interesse específicas, separada por virgulas.
* Expectativa: O método getAreasInteresse deve retornar as áreas de interesse esperadas.

5. Teste de getBairro
   
![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/c52eb285-d5aa-4dec-91f9-4312451f1242)

* Descrição: Este teste garante que o método getBairro retorne corretamente o bairro associado à instância.
* Cenário de Teste: Qaunado o usuario inicializada com um bairro específico.
* Expectativa: O método getBairro deve retornar o bairro esperado.

6. Teste de getTempoEx
   
   ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/1b1b1f81-1d9f-4b9b-9af3-dfbb9b31f4c9)

* Descrição: Este teste verifica se o método getTempoEx retorna corretamente o tempo de experiência associado à instância.
* Cenário de Teste: Qaundo o ususario inicializada com um tempo de experiência específico, apenas o número.
* Expectativa: O método getTempoEx deve retornar o tempo de experiência esperado.

7. Teste de getFtPerfil
   
   ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/700515f7-0800-4f22-940c-25acf1b3aca7)

* Descrição: Este teste valida se o método getFtPerfil retorna corretamente a URL da foto de perfil associada à instância.
* Cenário de Teste: Quando o usuario informa a sua foto de perfil específica, como não tem visual pode informar foto.img.
* Expectativa: O método getFtPerfil deve retornar a URL de foto de perfil esperada.

8. Teste de getHabilidades

   ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/e0595868-59ae-49c2-abbf-3e86e8573a46)

* Descrição: Este teste assegura que o método getHabilidades retorne corretamente as habilidades associadas à instância.
* Cenário de Teste: Quando o usuario inicializada com habilidades específicas.
* Expectativa: O método getHabilidades deve retornar as habilidades esperadas.

9. Teste de getNome

    ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/ef43e206-e05d-45ed-a29d-d7b2eed9758a)

* Descrição: Este teste verifica se o método getNome retorna corretamente o nome associado à instância.
* Cenário de Teste: Quando o usuario inicializada com um nome específico.
* Expectativa: O método getNome deve retornar o nome esperado.

10. Teste de getIdade

    ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/cf45f1a0-ef7a-4bf2-9a42-0a52fd7b84c0)

* Descrição: Este teste confirma se o método getIdade retorna corretamente a idade associada à instância.
* Cenário de Teste: Quando o usuario  inicializada com uma idade específica.
* Expectativa: O método getIdade deve retornar a idade esperada.

11. Teste de getEmail

    ![image](https://github.com/Troca-Servico/Entrega-3-Junit/assets/111398446/438ed71f-217d-4a96-b298-199543be8777)

* Descrição: Este teste assegura que o método getEmail retorne corretamente o e-mail associado à instância.
* Cenário de Teste: Quando o usuario inicializada com um e-mail específico.
* Expectativa: O método getEmail deve retornar o e-mail esperado.





