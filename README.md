# projeto-galeria-de-tenis-novoprojetocss


* {
  padding: 0;
  margin: 0;
  font-family: Helvetica;
  box-sizing: border-box;
}

/* Cabeçalho */
header {
  background-color:blue;
  text-align: center;
  padding: 15px;
  color: #fff;
}

/* Grid de produtos */
.container {
  background-color: #eee;
  min-height: 60vh;
  padding: 50px;
}

.products-container {
  max-width: 1200px;
  margin: 0 auto;
}

.card {
  width: 31%;
  margin: 1% 1%;
  display: inline-block;
  padding: 15px;
}

.product-image {
  height: 300px;
  width: 100%;
  margin-bottom: 10px;
  background-position: center;
  background-size: cover;
}

#img-1 {
  background-image: url('../img/tenis1.jpg');
}

#img-2 {
  background-image: url('../img/tenis2.jpg');
}

#img-3 {
  background-image: url('../img/tenis3.jpg');
}

#img-4 {
  background-image: url('../img/tenis4.jpg');
}

#img-5 {
  background-image: url('../img/tenis5.jpg');
}

#img-6 {
  background-image: url('../img/tenis6.jpg');
}

h3 {
  margin-bottom: 10px;
  color: blue;
  font-size: 24px;
}

.card p {
  margin-bottom: 10px;
}

.bold {
  font-weight: bold;
}

.btn {
  display: block;
  width: 100%;
  text-align: center;
  text-transform: uppercase;
  text-decoration: none;
  background-color: blue;
  color: #fff;
  padding: 15px;
  border-radius: 5px;
}

.btn:hover {
  background-color:blueviolet;
}

/* Rodapé */
footer {
  background-color: blue;
  text-align: center;
  padding: 80px;
  color: #fff;
}
