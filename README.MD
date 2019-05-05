13:35PM 05-05-19
-> sourceMap use to display browser pre compiled components


<==================================================================>
                    GRID BASICS
<==================================================================>


13:50PM 05-05-19
-> available classes to be used at the GRID System of Bootstrap

.container       => to apply the default width 
.container-fluid => to make the deiv fluid type design

    .row         => row separation

        .col         => specify the col auto adjust
        .col{xm, sm, md, lg, xl}-{12 col}


<==================================================================>
                ALIGNMENT HORIZONTALLY
<==================================================================>


15:04PM 05-05-19
-> aligning the column HORIZONTALLY via its row
row .justify-content-{start, center, end, around, between}


<==================================================================>
                ALIGNMENT VERTICALLY
<==================================================================>


15:18PM 05-05-19
-> align the column VERTICALLY based via its row
row .align-items-{start, center, end, strectch}


16:42PM 05-05-19
-> aligning the column via its own column

col .align-self-{start, center, end, stretch}


<==================================================================>
                    ORDERING COLUMN
<==================================================================>


16:45PM 05-05-2019
-> Changing the order of the element via its column

col .order-12    => Will be pushed to the right caused the lesser the number the more prioritize it will be gets

col .order-2     => Regardless if where this particular element resides it will be pushed onto the left cause is is in the 2nd order

OPTIONAL media-query by appending the desired device screen
ex. 

    order - {xs, sm, md, lg, xl} - {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12}
            ~ breakpoint_name ~  - 


<==================================================================>
                    OFFSETTING COLUMN
<==================================================================>


16:59PM 05-05-19

offseting a element via its column

col offset-2
           ~ number of space to be offseted on the left

Optionally can be inserted using the desired breakpoint

offset-{md}-2 => the offset will be applied only if the current screen size was in medium size


- xs => max-width:  575.98px
- sm => max-witdh:  767.98px
- md => max-width:  991.98px
- lg => max-width: 1199.98px
- xl => 1200px and beyond


<==================================================================>
                    NAVIGATION HEADER STRUCTURE
<==================================================================>


nav.navbar.navbar-{light}.bg-light
                  ~ theme ~ backgroun light color

a.navbar-brand{Brand_Name}

ul.navbar-nav
    li.nav-item
        a.nav-link {Page_Link}


// making the navigation mobile first approach

nav.navbar.{navbar-expand-lg}     .navbar-{light}.bg-light
          ~ expand at LG brkpoint  ~ theme        ~ background light color

a.navbar-brand{Brand_Name}

div.collapse.navbar-collapse
    ul.navbar-nav
        li.nav-item
            a.nav-link {Page_Link}


<==================================================================>
                    UTILITIES CLASS
<==================================================================>


.ml-auto    => automatically compute *MARGIN-LEFT* of the element      (push to the right)
.mr-auto    => automatically compute the *MARGIN-RIGHT* of the element (push to the left)

-primary
-secondary
-warning
-success
-danger
-info
-light
-dark

