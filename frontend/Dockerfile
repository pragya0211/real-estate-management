FROM node:18
WORKDIR /app
COPY . .
RUN npm install -g @angular/cli
RUN ng analytics off
RUN npm install
RUN npm run build 
EXPOSE 4200
CMD ["ng", "serve", "--host", "0.0.0.0", "--port", "4200"]
