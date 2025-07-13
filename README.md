📚 Pesquisa: Collection List em Java
📝 Descrição
Este repositório contém uma pesquisa em PDF sobre o uso da Collection List na linguagem Java. A pesquisa aborda os conceitos fundamentais, aplicações práticas, vantagens, desvantagens e exemplos de uso dessa estrutura da API de coleções do Java.

A List é uma das interfaces mais utilizadas da Collection Framework, sendo essencial para o trabalho com listas ordenadas e manipulação dinâmica de dados.

🔍 O que é uma Collection List?
A List é uma interface da Java Collection Framework que representa uma coleção ordenada de elementos, onde elementos duplicados são permitidos. Ela é amplamente utilizada para armazenar, acessar e manipular dados de forma sequencial.

Principais implementações:
ArrayList

LinkedList

Vector



✅ Vantagens
🔄 Ordem mantida: Os elementos são mantidos na ordem em que foram adicionados.

📥 Permite duplicatas: Útil quando é necessário armazenar itens repetidos.

🔢 Acesso por índice: Permite acessar elementos de forma direta por posição.

🛠️ Diversas implementações: Pode escolher entre diferentes estruturas dependendo da necessidade (ex: velocidade ou memória).

❌ Desvantagens
🧠 Consumo de memória: Algumas implementações, como ArrayList, podem desperdiçar memória se não forem dimensionadas corretamente.

🕒 Desempenho em certas operações: LinkedList pode ser lenta em operações de acesso direto (get(index)).

⚠️ Gerenciamento manual: Em alguns casos, é necessário gerenciar redimensionamento ou sincronização manualmente.



🧪 Exemplos de uso
java
Copiar
Editar
import java.util.ArrayList;
import java.util.List;

public class ExemploList {
    public static void main(String[] args) {
        List<String> nomes = new ArrayList<>();
        nomes.add("Leandro");
        nomes.add("Gabriel");
        nomes.add("José");

        for (String nome : nomes) {
            System.out.println(nome);
        }
    }
}
🎯 Objetivo da pesquisa
Compreender o funcionamento e aplicação da interface List

Comparar vantagens e desvantagens com outras coleções

Estimular boas práticas no uso de estruturas de dados em Java

👤 Autor
Leandro – Estudante de Desenvolvimento de Sistemas, entusiasta de Java e estruturas de dados.

