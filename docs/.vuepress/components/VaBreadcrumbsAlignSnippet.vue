<template>
  <div class="example">
    <va-breadcrumbs align="center">
      <va-breadcrumbs-item label="Application" />
      <va-breadcrumbs-item label="Dashboard" />
      <va-breadcrumbs-item label="Page" />
    </va-breadcrumbs>
    <br/>
    <va-breadcrumbs align="right">
      <va-breadcrumbs-item label="Application" />
      <va-breadcrumbs-item label="Dashboard" />
      <va-breadcrumbs-item label="Page" />
    </va-breadcrumbs>
    <br/>
    <va-breadcrumbs align="between">
      <va-breadcrumbs-item label="Application" />
      <va-breadcrumbs-item label="Dashboard" />
      <va-breadcrumbs-item label="Page" />
    </va-breadcrumbs>
  </div>
</template>

<script>
  import VaBreadcrumbs from '../../../src/components/vuestic-components/va-breadcrumbs/VaBreadcrumbs'
  import VaBreadcrumbsItem from '../../../src/components/vuestic-components/va-breadcrumbs/VaBreadcrumbsItem'
  import VaIcon from '../../../src/components/vuestic-components/va-icon/VaIcon'

  export default {
    components: { VaBreadcrumbs, VaBreadcrumbsItem, VaIcon },
  }
</script>
