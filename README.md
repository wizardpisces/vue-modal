  
  Usage

  <!-- use the modal component, pass in the prop -->
  <modal :show.sync="showModal">
    <!--
      you can use custom content here to overwrite
      default content
    -->
    <h3 slot="header">custom header</h3>
    <h3 slot="body">custom body</h3>
  </modal>
