FROM node:14
ARG API_KEY
ENV API_KEY='40c753f1aa3b116a3646ff57aaffbcb89e09c835320665188565ed9e42f889b3'
COPY . .
RUN ["npm", "install"]
CMD ["npm", "test"]