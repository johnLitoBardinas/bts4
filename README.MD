13:35PM 05-05-19
-> sourceMap use to display browser pre compiled components

13:50PM 05-05-19
-> available classes to be used at the GRID System of Bootstrap

.container       => to apply the default width 
.container-fluid => to make the deiv fluid type design

    .row         => row separation

        .col         => specify the col auto adjust
        .col{xm, sm, md, lg, xl}-{12 col}


15:04PM 05-05-19
-> aligning the column HORIZONTALLY via its row
row .justify-content-{start, center, end, around, between}


15:18PM 05-05-19
-> align the column VERTICALLY based via its row
row .align-items-{start, center, end, strectch}


16:42PM 05-05-19
-> aligning the column via its own column

col .align-self-{start, center, end, stretch}


16:45PM 05-05-2019
-> Changing the order of the element via its column

col .order-12    => Will be pushed to the right caused the lesser the number the more prioritize it will be gets

col .order-2     => Regardless if where this particular element resides it will be pushed onto the left cause is is in the 2nd order

OPTIONAL media-query by appending the desired device screen
ex. 

    order - {xs, sm, md, lg, xl} - {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12}