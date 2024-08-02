 mkdir ibge-clone
cd ibge-clone
npm init -y
npm install express sequelize pg pg-hstore body-parser cors

npx create-react-app client
cd client
npm install axios react-leaflet leaflet

const express = require('express');
const bodyParser = require('body-parser');
const cors = require('cors');
const { Sequelize } = require('sequelize');
const app = express();
const port = 5000;
