FROM node:alpine
LABEL maintainer="vinita121039@gmail.com"
WORKDIR /usr/src/pythoncodes
COPY subscriber.js /usr/src/pythoncodes
RUN npm install mqtt
CMD ["node", "sub.js"]