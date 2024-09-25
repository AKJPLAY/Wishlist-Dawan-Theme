Add this Code To Wishlist Icon on Header.


{% if pages['wishlist'] %}
  "<a href="{{ pages['wishlist'].url }}" class="header__icon header__icon--cart link focus-inset" id="wishlist-icon-bubble" style="margin-right: 0.1rem;">
      <svg class="icon main-icon-heart" width="22" height="20" viewBox="0 0 22 20" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M10.9998 19.1663C10.7127 19.1663 10.4359 19.0601 10.2202 18.867C9.40555 18.1391 8.62009 17.455 7.92711 16.8516L7.92357 16.8485C5.89186 15.0793 4.1374 13.5515 2.91668 12.0465C1.5521 10.3639 0.916504 8.76867 0.916504 7.02592C0.916504 5.3327 1.48471 3.7706 2.51633 2.62716C3.56027 1.47021 4.9927 0.833008 6.55022 0.833008C7.71432 0.833008 8.78042 1.20907 9.7188 1.95066C10.1924 2.32499 10.6217 2.78312 10.9998 3.3175C11.3782 2.78312 11.8073 2.32499 12.281 1.95066C13.2194 1.20907 14.2855 0.833008 15.4496 0.833008C17.007 0.833008 18.4396 1.47021 19.4835 2.62716C20.5151 3.7706 21.0832 5.3327 21.0832 7.02592C21.0832 8.76867 20.4477 10.3639 19.0832 12.0463C17.8624 13.5515 16.1081 15.0792 14.0767 16.8482C13.3825 17.4525 12.5958 18.1377 11.7793 18.8673C11.5637 19.0601 11.2868 19.1663 10.9998 19.1663ZM6.55022 2.04012C5.32658 2.04012 4.20248 2.53912 3.38472 3.44532C2.5548 4.36519 2.09768 5.63676 2.09768 7.02592C2.09768 8.49165 2.63081 9.80252 3.82614 11.2763C4.98147 12.7008 6.69993 14.1972 8.68964 15.9299L8.69333 15.933C9.38893 16.5388 10.1775 17.2255 10.9981 17.9588C11.8238 17.2241 12.6135 16.5363 13.3105 15.9296C15.3001 14.1969 17.0184 12.7008 18.1737 11.2763C19.3689 9.80252 19.902 8.49165 19.902 7.02592C19.902 5.63676 19.4449 4.36519 18.615 3.44532C17.7973 2.53912 16.6731 2.04012 15.4496 2.04012C14.5532 2.04012 13.7302 2.33128 13.0035 2.90544C12.356 3.41733 11.9048 4.06444 11.6404 4.51722C11.5043 4.75006 11.2649 4.88904 10.9998 4.88904C10.7347 4.88904 10.4953 4.75006 10.3593 4.51722C10.095 4.06444 9.64387 3.41733 8.99613 2.90544C8.26945 2.33128 7.44645 2.04012 6.55022 2.04012Z" fill="#2B2A30" stroke="#2B2A30" stroke-width="0.2"/>
      </svg>
      <div class="wishlist-count-bubble">
          <span aria-hidden="true">0</span>
        <span class="visually-hidden">0</span>
      </div>
  </a>"
{% endif %}  
