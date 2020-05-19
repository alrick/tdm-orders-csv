<template>
  <div>
    <table class="table">
      <thead>
        <tr>
          <th><abbr title="adresse ID">ID</abbr></th>
          <th>email</th>
          <th><abbr title="numéro de commande">#</abbr></th>
          <th>article</th>
          <th><abbr title="numéro d'article">art</abbr></th>
          <th><abbr title="pointure">p</abbr></th>
          <th><abbr title="quantité">q</abbr></th>
          <th>référence</th>
          <th>prix</th>
          <th>tva</th>
          <th>prénom</th>
          <th>nom</th>
          <th>entreprise</th>
          <th><abbr title="adresse de livraison">adresse</abbr></th>
          <th><abbr title="code postale">cp</abbr></th>
          <th>ville</th>
          <th>commentaire</th>
        </tr>
      </thead>
      <tfoot>
        <tr>
          <th><abbr title="adresse ID">ID</abbr></th>
          <th>email</th>
          <th><abbr title="numéro de commande">#</abbr></th>
          <th>article</th>
          <th><abbr title="numéro d'article">art</abbr></th>
          <th><abbr title="pointure">p</abbr></th>
          <th><abbr title="quantité">q</abbr></th>
          <th>référence</th>
          <th>prix</th>
          <th>tva</th>
          <th>prénom</th>
          <th>nom</th>
          <th>entreprise</th>
          <th><abbr title="adresse de livraison">adresse</abbr></th>
          <th><abbr title="code postale">cp</abbr></th>
          <th>ville</th>
          <th>commentaire</th>
        </tr>
      </tfoot>
      <tbody>
        <tr>
          <th>1</th>
          <td>roger@example.org</td>
          <td>#12567</td>
          <td>Reebok Print Premier Black</td>
          <td>IB1042 AK</td>
          <td>40</td>
          <td>1</td>
          <td>Roger Hanin</td>
          <td>120,70</td>
          <td>9.29</td>
          <td>George</td>
          <td>Hanin</td>
          <td>TDM.ch SA</td>
          <td>Impasse Abitbol</td>
          <td>8000</td>
          <td>Grandville</td>
          <td>blublu</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  props: {
    orders: {
      type: Array,
      default: null
    }
  }
}
</script>
