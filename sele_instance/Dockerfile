FROM betaquick/selenium-node
LABEL description="A kightweight selenium instance with port 4444 exposed"

RUN npm install -g webdriver-manager \
    && webdriver-manager update

EXPOSE 4444

ENTRYPOINT ["sh", "-c", "webdriver-manager start"]