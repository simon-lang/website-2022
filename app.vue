<template>
  <Head>
    <Title>Simon Lang: Pretty good web programmer, Brisbane, Australia</Title>
  </Head>
  <main>
    <div id="content">
      <img
        src="https://avatars.githubusercontent.com/u/339630?v=4"
        class="avatar"
      />
      <h1 class="mb-0">Simon Lang</h1>
      <h2>Full Stack Engineer</h2>
      <ul>
        <li>Over 15 years experience across diverse industries</li>
        <li>Language/framework agnostic</li>
        <li>Strong product focus</li>
        <li>Located in Brisbane but working remote since 2006</li>
        <li>Bachelor of Software Engineering</li>
        <li>Easy to get along with, love my job</li>
        <li>Proud father of twin girls</li>
        <li>Want to chat? <a href="mailto:simon@lang.au">simon@lang.au</a></li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: rgb(24, 41, 72);
  background: linear-gradient(
    159deg,
    rgba(24, 41, 72, 1) 0%,
    rgba(9, 73, 108, 1) 100%
  );
  color: #ddd;
  font-family: "Open Sans", "Helvetica", sans-serif;
  line-height: 1.4;
  font-size: 16px;
  overflow: hidden;
}
a {
  color: white;
}
.avatar {
  width: 4rem;
  height: 4rem;
  border-radius: 2rem;
  float: right;
  margin-top: 1rem;
  margin-right: 1rem;
}
.mb-0 {
  margin-bottom: 0;
}
main {
  /* should prob flex */
  height: 100vh;
  display: flex;
  align-items: center;
  margin: 0 auto;
  max-width: 680px;
}
#content {
  padding: 2rem;
  background: rgba(0, 0, 0, 0.1);
  animation: reveal 375ms 375ms ease forwards;
}
h1 {
  color: white;
}
p,
li {
  font-size: 1.1rem;
  margin-bottom: 0.2rem;
}
ul {
  padding-left: 1rem;
}
li {
  list-style-type: circle;
}
@keyframes reveal {
  0% {
    opacity: 0;
    transform: translateY(100px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
