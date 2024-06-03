<template>
    <div class='navbar'> 
         <div class='AppLogo'>
             <img src='../assets/InviteLogo.png' alt='logo'/>
         </div>
 
         <div class='menu'>
             <ul>
                 <li><router-link to='/'>Home</router-link></li>
                 <li><router-link to='/events'>Events</router-link></li>
                 <li><router-link to='/finance'>Finance</router-link></li>
                 <li><router-link to='/map'>Map</router-link></li>
             </ul>
         </div>
 
         <div class='icons'>
             <ul>
                 <li><router-link to='#' class = "navCreateEvent">Create Event</router-link></li>
                 <li><router-link to='#'><img src='../assets/ticket_icon.png' alt='Tickets'/></router-link></li>
                 <li><router-link to='#'><img src='../assets/star_icon.png' alt='Interested'/></router-link></li>
                 <li class="profile-dropdown">
                     <router-link to='#'><img src='../assets/profile_icon.png' alt='Profile'/></router-link>
                     <div class="dropdown-content">
                         <router-link to='#'>Are you an Organizer?</router-link>
                         <router-link to='#'>Logout</router-link>
                     </div>
                 </li>
             </ul>
         </div>
    </div>
 </template>
 
 <script>
 export default {
     name: 'NavBar',
 }
 </script>
 
 <style>
 @import '../assets/styles.css';
 </style>
 