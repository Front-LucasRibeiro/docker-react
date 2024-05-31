FROM node:20.14.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

# Etapa de build para produção
RUN npm run build

# Etapa de ambiente de desenvolvimento
CMD npm run dev