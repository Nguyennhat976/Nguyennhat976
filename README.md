// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBiR_H16mTMoGMlADKsYbL50moqliqGXJ8",
  authDomain: "home-wolds-74aee.firebaseapp.com",
  projectId: "home-wolds-74aee",
  storageBucket: "home-wolds-74aee.appspot.com",
  messagingSenderId: "370412406766",
  appId: "1:370412406766:web:7bcb3e958027592ab0b0ff",
  measurementId: "G-HJ21W9B1RD"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
npm install -g firebase-tools
firebase login
firebase init
firebase deploy
