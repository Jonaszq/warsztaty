    <template>
  <section class="about">
    <h2>About You</h2>
    <div class="about-content">
      <p>{{ aboutText }}</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutUs',
  data() {
    return {
      aboutText: 'Short description about you :)'
    };
  }
}
</script>

<style scoped>
.about {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 35px 20px;
  background: #1c1c1e;
  color: #ffffff;
  max-width: 1200px;
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 0 32px 6px rgba(30, 72, 143, 1);
}
.about h2 {
  margin: 0 0 10px;
  font-size: 2rem;
  color: #1e488f;
}
.about-content {
  margin: 10px;
  padding: 20px;
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid #A3CFFF;
  border-radius: 8px;
  font-size: 1.2rem;
  line-height: 1.5;
}
</style>

