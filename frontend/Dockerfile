FROM node:16
WORKDIR /frontend
COPY . .
RUN npm install
RUN npm run build
RUN npm install -g serve
CMD ["serve", "-s", "build"]
EXPOSE 3000
