# Javascript

Eventi per interagire con il DOM

## Descrizione

```bash

<button id="myButton">Click me</button>
        <p id="myText"></p>

```

## è bene capire che all'ID "myButton" è associato

```bash

<script>
    document.getElementById("myButton").addEventListener("click", () => {
        document.getElementById("myText").textContent = "Button was clicked!";
    });
</script>

```