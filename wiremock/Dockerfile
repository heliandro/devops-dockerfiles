FROM wiremock/wiremock:2.35.0
COPY /src/mocks /home/wiremock
CMD [ "/docker-entrypoint.sh", "--global-response-templating" ]
