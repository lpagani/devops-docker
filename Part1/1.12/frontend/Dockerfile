FROM node
COPY . .
RUN npm install
# Open port 5000
EXPOSE 5000
ENV API_URL=http://172.16.172.146:8000
CMD npm start
