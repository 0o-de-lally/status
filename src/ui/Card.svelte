<script>
  export let title
</script>

<div class="uk-card uk-card-default uk-card-body uk-margin-left uk-margin-bottom">
  <h5 class="uk-card-title">{title}</h5>
  <slot name="body"/>
</div>
