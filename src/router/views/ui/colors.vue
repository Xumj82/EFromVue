<script>
import Layout from "../../layouts/main";
import PageHeader from "@/components/page-header";
import appConfig from "@/app.config";

/**
 * Colors component
 */
export default {
  page: {
    title: "Colors",
    meta: [{ name: "description", content: appConfig.description }]
  },
  components: { Layout, PageHeader },
  data() {
    return {
      title: "Colors",
      items: [
        {
          text: "Veltrix",
          href: "/"
        },
        {
          text: "UI Elements",
          href: "/"
        },
        {
          text: "Colors",
          active: true
        }
      ]
    };
  }
};
</script>

<template>
  <Layout>
    <PageHeader :title="title" :items="items" />
    <div class="row">
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-primary">
              <h5 class="my-2 text-white">#626ed4</h5>
            </div>
            <h5 class="mb-0 mt-4 text-primary text-center font-size-18">Primary</h5>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-success">
              <h5 class="my-2 text-white">#02a499</h5>
            </div>
            <h5 class="mb-0 mt-4 text-success text-center font-size-18">Success</h5>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-info">
              <h5 class="my-2 text-white">#38a4f8</h5>
            </div>
            <h5 class="mb-0 mt-4 text-info text-center font-size-18">Info</h5>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-warning">
              <h5 class="my-2 text-white">#f8b425</h5>
            </div>
            <h5 class="mb-0 mt-4 text-warning text-center font-size-18">Warning</h5>
          </div>
        </div>
      </div>
    </div>
    <!-- end row -->

    <div class="row">
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-danger">
              <h5 class="my-2 text-white">#ec4561</h5>
            </div>
            <h5 class="mb-0 mt-4 text-danger text-center font-size-18">Danger</h5>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-dark">
              <h5 class="my-2 text-white">#343a40</h5>
            </div>
            <h5 class="mb-0 mt-4 text-dark text-center font-size-18">Dark</h5>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-md-6">
        <div class="card">
          <div class="card-body text-center">
            <div class="color-box p-4 rounded bg-secondary">
              <h5 class="my-2 text-white">#6c757d</h5>
            </div>
            <h5 class="mb-0 mt-4 text-muted text-center font-size-18">Secondary</h5>
          </div>
        </div>
      </div>
    </div>
    <!-- end row -->
  </Layout>
</template>