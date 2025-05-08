## Exercício 06

### Testes

package org.example;


import static org.junit.jupiter.api.Assertions.*;

import java.util.List;

import org.junit.jupiter.api.Test;

class RestauranteTest {

    @Test
    void testRestauranteCardapio() {
        Restaurante restaurante = new Restaurante("Sabor da Serra", "Rua das Acácias, 123");

        // Criando pratos
        Prato prato1 = new Prato("Lasanha", 32.50, false, "Lasanha de carne com queijo");
        Prato prato2 = new Prato("Salada Verde", 18.00, true, "Salada com folhas frescas");

        // Adicionando pratos
        restaurante.adicionarPrato(prato1);
        restaurante.adicionarPrato(prato2);

        // Verificando se os pratos foram adicionados corretamente
        assertEquals(2, restaurante.getCardapio().size());

        // Verificando propriedades dos pratos
        Prato p1 = restaurante.getCardapio().get(0);
        Prato p2 = restaurante.getCardapio().get(1);

        assertEquals("Lasanha", p1.getNome());
        assertFalse(p1.isVegetariano());
        assertTrue(p2.isVegetariano());
        assertEquals("Salada Verde", p2.getNome());

        // Removendo um prato
        restaurante.removerPrato(prato1);
        assertEquals(1, restaurante.getCardapio().size());
        assertEquals("Salada Verde", restaurante.getCardapio().get(0).getNome());
    }
}
