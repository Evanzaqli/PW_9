<template>
    <div id="app">
        <nav>
            <ul>
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/About">About</router-link></li>
                <li><router-link to="/Services">Services</router-link></li>
            </ul>
        </nav>
    <Router/>
    </div>
   </template>
   <script>
   export default {
    name: 'App'
   }
   </script>
   <style>
   nav ul {
    list-style-type: none;
    padding: 0;
   }
   nav ul li {
    display: inline;
    margin-right: 10px;
   }
   </style>