<template>
    <div>
        <AppHeader/>
        <AboutMe/>
        <MyExperience/>
        <ContactMe/>
        <AppFooter/>
    </div>
</template>
<script>
import AppHeader from './AppHeader'
import AboutMe from './AboutMe'
import MyExperience from './MyExperience'
import ContactMe from './ContactMe'
import AppFooter from './AppFooter'
export default {
    components: {
        AppHeader,
        AboutMe,
        MyExperience,
        ContactMe,
        AppFooter
    }
}
</script>