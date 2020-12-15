<div class="notification" v-show="isActive">
      Ceci est une notification.

        <button class="close" v-on:click="isActive = false">
          x
        </button>
      </div>

<script>
export default {
data () {
  return {
    isActive : true
  }
 }
}
<script>


<style>
	.notification {
	  display:flex;
	  justify-content: space-between;
	  background-color:red;
	  padding: 1.5rem;
	}
</style>