function encriptarTexto() {
    let texto = document.getElementById("inputText").value;
    let textoEncriptado = texto
        .replace(/e/g, "enter")
        .replace(/i/g, "imes")
        .replace(/a/g, "ai")
        .replace(/o/g, "ober")
        .replace(/u/g, "ufat");
    document.getElementById("outputText").value = textoEncriptado;
}

function desencriptarTexto() {
    let textoEncriptado = document.getElementById("inputText").value;
    let texto = textoEncriptado
        .replace(/enter/g, "e")
        .replace(/imes/g, "i")
        .replace(/ai/g, "a")
        .replace(/ober/g, "o")
        .replace(/ufat/g, "u");
    document.getElementById("outputText").value = texto;
}

function copiarTexto() {
    let texto = document.getElementById("outputText");
    texto.select();
    document.execCommand("copy");
    alert("Texto copiado al portapapeles!");
}
