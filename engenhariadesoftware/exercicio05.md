## Exercicio 05

### Classe Restaurante

package org.example;


import java.util.LinkedList;
import java.util.List;

public class Restaurante {

    private String nome;
    private String endereco;
    private List<Prato> cardapio = new LinkedList<>();

    public Restaurante(String nome, String endereco) {
        this.nome = nome;
        this.endereco = endereco;
    }

    public void adicionarPrato(Prato prato) {
        cardapio.add(prato);
    }

    public void removerPrato(Prato prato) {
        cardapio.remove(prato);
    }

    public List<Prato> getCardapio() {
        return cardapio;
    }

    public void exibirPratos() {
        for (Prato prato : cardapio) {
            System.out.println(prato);
        }
    }

    // Getters e setters para nome e endereco

    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public String getEndereco() {
        return endereco;
    }

    public void setEndereco(String endereco) {
        this.endereco = endereco;
    }
}

### Classe Prato

package org.example;

public class Prato {

    private String nome;
    private double preco;
    private boolean vegetariano;
    private String descricao;

    public Prato(String nome, double preco, boolean vegetariano, String descricao) {
        this.nome = nome;
        this.preco = preco;
        this.vegetariano = vegetariano;
        this.descricao = descricao;
    }

    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public double getPreco() {
        return preco;
    }

    public void setPreco(double preco) {
        this.preco = preco;
    }

    public boolean isVegetariano() {
        return vegetariano;
    }

    public void setVegetariano(boolean vegetariano) {
        this.vegetariano = vegetariano;
    }

    public String getDescricao() {
        return descricao;
    }

    public void setDescricao(String descricao) {
        this.descricao = descricao;
    }

    @Override
    public String toString() {
        return "Prato: " + nome + " | Preço: R$" + preco +
                " | Vegetariano: " + (vegetariano ? "Sim" : "Não") +
                " | Descrição: " + descricao;
    }
}
