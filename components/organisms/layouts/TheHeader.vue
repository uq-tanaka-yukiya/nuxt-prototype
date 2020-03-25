<template>
  <header>
    <HeaderTop></HeaderTop>
    <HeaderContainer></HeaderContainer>
    <HeaderServiceNav></HeaderServiceNav>
    <HeaderGlobalNav></HeaderGlobalNav>
  </header>
</template>

<script>
import HeaderTop from '../../molecules/layouts/header/HeaderTop'
import HeaderContainer from '../../molecules/layouts/header/HeaderContainer'
import HeaderServiceNav from '../../molecules/layouts/header/HeaderServiceNav'
import HeaderGlobalNav from '../../molecules/layouts/header/HeaderGlobalNav'

export default {
  components: {
    HeaderTop,
    HeaderContainer,
    HeaderServiceNav,
    HeaderGlobalNav,
  }
}
</script>
