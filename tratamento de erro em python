from datetime import datetime

def calcular_idade(ano_nascimento):
    ano_atual = datetime.now().year
    idade = ano_atual - ano_nascimento
    return idade

def obter_ano_nascimento():
    while True:
        try:
            ano_nascimento = int(input("Digite o ano de nascimento (1922-2021): "))
            if 1922 <= ano_nascimento <= 2021:
                return ano_nascimento
            else:
                print("Ano não permitido. Tente novamente.")
        except ValueError:
            print("Por favor, digite um valor numérico válido.")

# Solicita informações do usuário
nome_completo = input("Digite seu nome completo: ")
ano_nascimento = obter_ano_nascimento()

# Calcula a idade
idade = calcular_idade(ano_nascimento)

# Exibe as informações do usuário
print("\nInformações do usuário:")
print("Nome: ", nome_completo)
print("Idade: ", idade, "anos")
