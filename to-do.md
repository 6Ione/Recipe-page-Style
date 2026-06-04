## To Do list

* Fix mobile viewport its broken.


## Remove this code as its broken
*     /* ── Tablet and up: desktop card layout ── */
    @media (min-width: 375px) {
      .body {
        padding: 80px 0;
      }
    }
 
    /* ── Mobile: phones only (up to 599px) ── */
    @media (max-width: 1440px) {
      .body {
        padding: 0;
        background-color: white;
      }
 
      .container {
        display: block;
      }
 
      .card {
        border-radius: 0;
        padding: 0 0 32px;
      }
 
      .card-image img {
        border-radius: 0;
      }
 
      .card-recipe-name {
        padding: 0 28px;
        margin-top: 28px;
      }
 
      .card-prep-time {
        margin: 24px 28px 0;
        border-radius: 12px;
      }
 
      .card-ingredients, .card-instructions, .card-nutritions {
        padding: 0 28px;
      }
 
      hr {
        margin: 0 28px;
      }

      .card-nutritions {
        padding: 0 28px;
      }
      .card-recipe-name h1 {
        font-size: 2rem;
      }
    }