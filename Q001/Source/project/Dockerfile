FROM node:latest
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 5000
CMD npm run dev -- --host --port 5000