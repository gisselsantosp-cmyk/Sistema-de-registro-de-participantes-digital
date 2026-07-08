// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyC5uEShNquHIYTztwpW5aOlK-2ME4ahYqQ",
  authDomain: "registro-de-participante-8d484.firebaseapp.com",
  databaseURL: "https://registro-de-participante-8d484-default-rtdb.firebaseio.com",
  projectId: "registro-de-participante-8d484",
  storageBucket: "registro-de-participante-8d484.firebasestorage.app",
  messagingSenderId: "1096110418081",
  appId: "1:1096110418081:web:7871d0f1eb2f8a2ad928e0",
  measurementId: "G-FXC3YJFV9Z"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
