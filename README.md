# Tablero-de-ajedrez-
Tablero de ajedrez 
.tablero {
 display: grid;
 grid-template-columns: repeat(8, 1fr);
 grid-template-rows: repeat(8, 1fr);
 grid-gap: 1px;
}

.casilla {
 background-color: white;
 width: 64px;
 height: 64px;
 display: flex;
 justify-content: center;
 align-items: center;
}

.casilla:nth-child(odd) {
 background-color: black;
}

.pieza {
 font-size: 24px;
 color: white;
}
