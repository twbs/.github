 <script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/9.12.1/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.12.1/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyCyzQHHFELq0fmsDK0l9yxbTfr2raA4sHA",
    authDomain: "pgclub-99.firebaseapp.com",
    projectId: "pgclub-99",
    storageBucket: "pgclub-99.appspot.com",
    messagingSenderId: "961833117710",
    appId: "1:961833117710:web:c977d9ced0d5703046345f",
    measurementId: "G-N2GN867SEF"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
