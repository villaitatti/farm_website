---
layout: default
title: "Rosso Toscano 2024"
description: "Vino Rosso Toscano, annata 2024"
---

# Rosso Toscano 2024

<style>
  .wine-page {
    display: flex;
    align-items: flex-start;
    flex-wrap: wrap;
  }

  /* Left column: nutritional info */
  .wine-info {
    flex: 1 1 300px; /* allows shrinking or growing, minimum about 300px */
    margin-right: 20px; /* space between the two columns */
  }

  /* Right column: image */
  .wine-image {
    flex: 0 1 auto; /* let image column be as wide as needed */
    text-align: left;
  }

  .wine-image img {
    max-width: 300px;
    height: auto;
    display: block;
    margin: 0; /* ensure no extra margin on the left */
  }

  /* Responsive design: On small screens, stack the columns */
  @media (max-width: 600px) {
    .wine-page {
      flex-direction: column;
    }

    .wine-info, .wine-image {
      margin-right: 0;
      margin-bottom: 20px; /* add space between stacked sections */
    }

    .wine-image img {
      max-width: 100%; /* full width on mobile */
    }
  }

  /* You might also want to style the table a bit */
  .nutritional-values {
    border-collapse: collapse;
    width: 100%;
    max-width: 300px;
  }

  .nutritional-values th, 
  .nutritional-values td {
    border: 1px solid #ccc;
    padding: 8px;
    text-align: left;
  }

  .nutritional-values th {
    background-color: #f8f8f8;
    font-weight: bold;
  }
</style>

<div class="wine-page">

  <!-- Left Column -->
  <div class="wine-info">
    <table class="nutritional-values">
      <tr>
        <th>Valori nutrizionali medi</th>
        <th colspan="2">100 ml</th>
      </tr>
      <tr>
        <td rowspan="2">Energia</td>
        <td>Kj</td>
        <td>322</td>
      </tr>
      <tr>
        <td>Kcal</td>
        <td>77</td>
      </tr>
      <tr>
        <td>Grassi</td>
        <td>g</td>
        <td>0</td>
      </tr>
      <tr>
        <td>di cui saturi</td>
        <td>g</td>
        <td>0</td>
      </tr>
      <tr>
        <td>Carboidrati</td>
        <td>g</td>
        <td>0,06</td>
      </tr>
      <tr>
        <td>di cui zuccheri</td>
        <td>g</td>
        <td>0,06</td>
      </tr>
      <tr>
        <td>Fibre</td>
        <td>g</td>
        <td>0</td>
      </tr>
      <tr>
        <td>Proteine</td>
        <td>g</td>
        <td>0</td>
      </tr>
      <tr>
        <td>Sale</td>
        <td>g</td>
        <td>0</td>
      </tr>
    </table>

    <h3>Ingredienti:</h3>
    <ul>
      <li>Uva</li>
    </ul>

    <h3>Conservanti:</h3>
    <ul>
      <li>Metabisolfito di potassio</li>
    </ul>

    <h3>Stabilizzanti:</h3>
    <ul>
      <li>Poliaspartato di potassio</li>
      <li>Gomma arabica</li>
    </ul>

  </div>

  <!-- Right Column -->
  <div class="wine-image">
    <img src="/assets/images/vino/rosso-toscano/2024-rosso-toscano-label.png" alt="Etichetta Rosso Toscano 2024">
  </div>

</div>
