<template>
  <div class="profile">
    <SimpleTitleBox title="My account"></SimpleTitleBox>
    <UserDetails> </UserDetails>
  </div>
</template>

<script>
import SimpleTitleBox from "@/components/common/SimpleTitleBox";
import UserDetails from "@/components/user/UserDetails";

export default {
  components: {
    SimpleTitleBox,
    UserDetails,
  },
};
</script>

