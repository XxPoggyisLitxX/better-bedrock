<script setup>
    // Here we're using the composition API with the <script setup> feature.
    // Everything in this script runs in the Vue component's setup function and
    // any declared variables can be accessed from the component's template.
    
    // defineProps lets you access the component's props from the setup function.
    import { defineProps } from 'vue'
    
    </script>
    
    <template>
    <div class="post">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!-- Auto width -->
<button class="btn"><i class="fa fa-download"></i> Download</button>

<!-- Full width -->
<button class="btn" style="width:100%"><i class="fa fa-download"></i> Download</button>
    </div>
    </template>
    
    <style scoped>
   /* Style buttons */
.btn {
  background-color: DodgerBlue;
  border: none;
  color: white;
  padding: 12px 30px;
  cursor: pointer;
  font-size: 20px;
}

/* Darker background on mouse-over */
.btn:hover {
  background-color: RoyalBlue;
}
    </style>