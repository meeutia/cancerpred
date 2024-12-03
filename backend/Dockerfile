FROM node:18

WORKDIR /app
ENV PORT 4000
ENV HOST 0.0.0.0

COPY . .
RUN npm install
EXPOSE 4000
CMD [ "npm", "run", "start"]
