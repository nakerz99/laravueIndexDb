<template>
    <div>
        <Navbar />
        <Content />
        <Footer />
        <Notifications />
    </div>
</template>

<script>
    import Navbar from '../Components/Navbar';
    import Content from '../Components/Content';
    import Footer from '../Components/Footer';
    import Notifications from '../Components/Notifications';

    export default {
        components: { Navbar, Content,  Footer, Notifications, },
    }
</script>
