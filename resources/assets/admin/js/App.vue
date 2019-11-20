<template>
    <div class="wrapper" style="position: relative">
        <app-header></app-header>
        <app-aside></app-aside>
        <div class="content-wrapper">
<!--            <app-breadcrumb :list="list"></app-breadcrumb>-->
<!--            <section class="content">-->
<!--                <router-view></router-view>-->
<!--            </section>-->
        </div>
        <app-footer></app-footer>
        <app-control-sidebar></app-control-sidebar>
        <div class="control-sidebar-bg"></div>
    </div>
</template>

<script>
    import AppHeader from "./components/header/Header";
    import AppAside from "./components/aside/Aside";
    import AppBreadcrumb from "./components/breadcrumb/Breadcrumb";
    import AppFooter from "./components/footer/Footer";
    import AppControlSidebar from "./components/control_siderbar/ControlSidebar";

    export default {
        name: "App",
        components: {
            AppHeader,
            AppAside,
            AppBreadcrumb,
            AppControlSidebar,
            AppFooter,
        }
    }
</script>
