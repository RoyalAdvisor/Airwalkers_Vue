<template>
  <div class="form-container p-3">
    <div class="mb-3 mt-3">
      <label for="exampleFormControlInput1" class="form-label">Fullname</label>
      <input
        type="text"
        class="form-control shadow-lg"
        id="exampleFormControlInput1"
        placeholder="Your Name..."
      />
      <div class="mb-3 mt-3">
        <label for="exampleFormControlInput1" class="form-label"
          >Email Address</label
        >
        <input
          type="email"
          class="form-control shadow-lg"
          id="exampleFormControlInput1"
          placeholder="name@example.com"
        />
      </div>
      <div class="mb-3 mt-3">
        <label for="exampleFormControlTextarea1" class="form-label"
          >Message</label
        >
        <textarea
          class="form-control shadow-lg"
          id="exampleFormControlTextarea1"
          rows="5"
          placeholder="Your Message..."
        ></textarea>
      </div>
      <div class="mb-3 mt-3 submit">
        <button class="btn btn-white text-center text-center">Submit</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Form",
};
</script>

<style scoped>
.form-container {
  margin: 2rem 0;
  min-width: 450px;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.form-container > div {
  width: 100%;
}
.form-label {
  font-size: 18px;
  font-weight: 600;
  color: #fff;
}
.form-control {
  border: 3px solid rgba(0, 0, 0, 20%);
}
.form-control::placeholder {
  font-weight: 600;
}
button {
  font-size: 16px;
  font-weight: 600;
  height: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #fff;
  transition: 200ms ease-in-out;
}
button:hover {
  color: #fff;
  background-color: #0f0f0f;
}
.submit {
  display: flex;
  justify-content: center;
  align-items: center;
}
@media screen and (max-width: 768px) {
  .form-container {
    min-width: 70%;
  }
}
@media screen and (max-width: 440px) {
  .form-container {
    min-width: 100%;
  }
}
</style>
