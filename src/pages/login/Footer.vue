 <template>
  <footer class="py-2 text-center">
    <p>{{ currentYear }} Culqui. Todos los derechos reservados.</p>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>
