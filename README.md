# Cálculo Numérico

Este notebook foi desenvolvido para a disciplina de Cálculo Numérico (SME0104) e contém soluções às questões 1–5 do trabalho prático.

---

## Estrutura do Notebook

1. **Cabeçalho**: Importação de bibliotecas e definição de funções auxiliares (por ex. `mmq`, `mmq_QR`, interpoladores, Francis, etc.).
2. **Questão 1: Sistemas Lineares**

   * Decomposição LU (funções `func1` e `func2`).
   * Comparação de tempos e medidas de erro.
3. **Questão 2: Zeros de Funções e Sistemas Não Lineares**

   * (a) Método da bisseção para raiz univariada.
   * (b) Método de Newton para sistema 2×2.
4. **Questão 3: Decomposição em Valores Singulares (SVD)**

   * Implementação QR iterativa (Francis).
   * Compressão de imagem com SVD.
5. **Questão 4: Interpolação**

   * (a) Lagrange e Newton.
   * (b) Nós equiespaçados (11 e 21 nós).
   * (c) Splines lineares e cúbicas.
   * (d) Nós de Chebyshev.
6. **Questão 5: Mínimos Quadrados**

   * Ajuste exponencial e polinomial (grau 4–6).
   * Cálculo de resíduos (RSS) em domínios original e log.
   * Comparações em subintervalos (20 dias iniciais e 50 dias finais).

---

## Instruções de Uso

1. **Ambiente**: Abra este arquivo no Google Colab.
2. **Bibliotecas**: Certifique-se de que `numpy`, `pandas`, `matplotlib` e `scipy` estão instaladas (Colab já inclui essas bibliotecas).
3. **Dados**: Faça upload do arquivo `casosacumuladosbrasilatuaizado.txt` e da imagem `cat.png` (para a Questão 3) na raiz do Colab.
4. **Execução**:

   * Execute célula a célula na ordem apresentada.
   * Revise e comente conforme necessário.
5. **Reprodutibilidade**:

   * Sementes aleatórias (`np.random.seed`) estão definidas para experimentos que usam ruído.
   * As fórmulas e critérios de parada (tolerâncias, número máximo de iterações) estão documentados em cada seção.

---