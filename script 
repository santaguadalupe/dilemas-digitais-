```javascript
function mostrarResposta(opcao) {

    const resposta = document.getElementById("resposta");
    const titulo = document.getElementById("titulo-resposta");
    const texto = document.getElementById("texto-resposta");

    resposta.style.display = "block";

    if (opcao === "A") {

        titulo.textContent = "⚠️ Não é a melhor opção.";

        texto.textContent =
            "Ignorar pode fazer com que a situação continue. " +
            "Sua imagem e sua privacidade são importantes.";

    }

    else if (opcao === "B") {

        titulo.textContent = "✅ Boa escolha!";

        texto.textContent =
            "Conversar e pedir a remoção da foto é um bom primeiro passo. " +
            "Explique que você não autorizou a publicação e peça que ela seja retirada.";

    }

    else if (opcao === "C") {

        titulo.textContent = "❌ Evite fazer isso.";

        texto.textContent =
            "Compartilhar a foto para se vingar pode aumentar o problema " +
            "e também desrespeitar a privacidade de outra pessoa.";

    }

    else if (opcao === "D") {

        titulo.textContent = "🟡 Pode ser necessário em alguns casos.";

        texto.textContent =
            "A denúncia pode ser importante quando a pessoa se recusa a remover " +
            "a publicação ou quando existe assédio, ameaça ou outro comportamento grave. " +
            "Quando possível, conversar primeiro pode resolver a situação.";

    }

    resposta.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });
}
```
