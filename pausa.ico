
void pausa(unsigned int milisegundos)
{
  volatile unsigned long compara=0;
  volatile int contador =0;
  do
  {
    if (compara!=millis())
    {
      contador++;
      compara=millis();
    }
  }
  while(contador<=milisegundos);
  return;
}
