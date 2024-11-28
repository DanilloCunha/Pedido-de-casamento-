
Nesse código abaixo : É simulação de um pedido de casamento.

print "Qual é o seu nome? "
nome = gets.chomp

# Faz a pergunta
puts "Olá, #{nome}, você aceita casar comigo? (sim/não)"
resposta = gets.chomp.downcase

# Verifica a resposta e exibe a reação
if resposta == "sim"
  puts "😀 Que alegria, #{nome}! Estou muito feliz!"
elsif resposta == "não"
  puts "😢 Poxa, #{nome}, tudo bem... Vou sobreviver!"
else
  puts "🤔 Não entendi sua resposta, #{nome}."
end

dei muitos residas kkkkkkkk.
