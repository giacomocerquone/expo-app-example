# Developing con react native

1. Non abbiamo html tags come html, p, or div, ma abbiamo View, Button, TouchableHighlight, ScrollView, FlatList
https://miro.medium.com/max/1400/0*NmU6pFk-P7fu19wf

2. In React native non c'è una gestione automatica dell'overflow come quella che abbiamo nel css in web https://www.w3schools.com/cssref/pr_pos_overflow.asp
(esempio in html https://jsfiddle.net/1vu5gymc/1/)

3. Official React Native guides: https://reactnative.dev/docs/getting-started 
and api https://reactnative.dev/docs/accessibilityinfo

4. https://snack.expo.dev/ Playground per react native basato su Expo: il tool per evitare di gestire codice nativo quando si scrive codice react native

5. Per creare un progetto Expo in locale:
npm install -g expo-cli
expo init newRnApp
cd newRnApp
expo start (oppure npm run start oppure yarn start)
"open simulator "

6. L'unico layouting disponibile in react native è flex ma non abbiamo css https://yogalayout.com/docs/
Esercitatevi qui: https://flexboxfroggy.com/#it