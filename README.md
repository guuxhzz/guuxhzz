/* Define a animação */
@keyframes example {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/* Aplica a animação ao elemento */
.animate {
  animation: example 2s ease-in-out infinite;
}
