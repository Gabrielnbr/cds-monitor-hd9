# Problema de Negócio

Em construção

Situação Problema: A Empresa precisa prever 2 meses da utilização da máquina virtual, pois ela possui limitações de negócio. Desta forma você terá que dizer se o bugget irá acabar até o final do contrato, quando irá acabar, se acabar quanto será que a empresa vai ter que gastar a mais.

Limitações: Recurso anual alocado máximo 2.000,00 dólares.

Os dados que devem ser consumidos devem está nesse range de data:
df = df.loc[df['date']>='2023-03-12' ,['date','cost']].groupby('date').sum().reset_index()

Renovação do Contrato da Máquina UNICIN: 12 Mar 2025

'maquina' UNICIN - renovação de contrato: 12 Mar 2025 - Mais estável na sua utilização sem ocilação de teste. Dados mais reais e confiáveis. Ação: Pode ser trabalhado.