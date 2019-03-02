FROM node:8-alpine
MAINTAINER Raghava Reddy "raghavareddy@in.ibm.com"
COPY . /worklog
WORKDIR /worklog
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]
