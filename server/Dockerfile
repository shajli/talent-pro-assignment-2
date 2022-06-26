FROM node:16.15.1

WORKDIR /app

COPY package.json

RUN npm install

ENV PORT 4000
ENV MONODB_URL "MongoDB Cloud Atlas URL, see .env.example file"
ENV CLOUD_NAME = 'Cloudinary Cloud name, see .env.example file'
ENV API_KEY = 'Cloudinary api_key, see .env.example file'
ENV API_SECRET = 'Cloudinary secret_key, see .env.example file'

EXPOSE $PORT

CMD ["npm run", "start:dev"]