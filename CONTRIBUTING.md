# Contribuindo com Exemplos

Ao contribuir para este repositório, primeiro discuta a alteração e propostas de exemplos que deseja fazer por meio de [issues](./issues), e-maili, whatsapp, telegram, ou qualquer outro método.

Observe que temos um código de conduta, siga-o em todas as suas interações com o projeto.
Processo de PR (pull request):

- Certifique-se que se ouver mais de um arquivo referente ao mesmo exemplo, que estejam todos em um mesmo diretório, com nome que identifique claramente do que se trata o exemplo.
- Não use nomes de arquivos e diretórios com espaço, ífens e com mais de 32 caracteres, também não inicie os nomes com números ou qualquer símbolo.
- Atualize o README.md com detalhes, links para localizações de arquivos úteis e parâmetros de execução, descrição das formulas em detalhes.
- Aumente os números de versão em quaisquer arquivos de exemplo e o README.md para a nova versão que este PR representaria. O esquema de controle de versão que usamos é SemVer.
- Você pode mesclar o PR depois de obter a aprovação dos outros desenvolvedores ou, se não tiver permissão para fazer isso, pode solicitar que o segundo revisor faça a mesclagem para você.


Para Evitar problemas nos testes e constantes commits desnecessários, os arquivos de nomes comuns (genericos) como `prog_32.hex` serão usados localmente e não serão mais enviados ao repositório, assim deve-se somente usar nomes que descrevam o exemplo a ser apresentados para representar a memória.

Para apresentar um exemplo crie um arquivo com um nome que descreva de forma simplicada o exemplo, por exemplo `exemplo_servo_control.hex`, quando for usar este exemplo em seu teste copie este arquivo para `prog_32.hex` sobrescrevendo o antigo. Não altere o código fonte para apontar para o novo exemplo, caso você deposite o novo código esta alteração pode atrapalhar outros desenvolvedores.

Faça o _commit_ apenas do aquivo que tem o nome que representa o exemplo, sempre ignorando o arquivo `prog_32.hex`

## Exemplos em C/C++ ou outra linguagem.

Exemplos em C/C++ ou qualquer outra linguagem podem ser apresentados, desde que sejam acompanhados de scripts e Makefile que gerem o assembly adequado para rodar em um processador RISC-V, lembrando que o RISCuinho até o momento está focado apenas em RV32I, outras extensões só poderão ser testadas caso se comprometam em contribuir com a implementação.

## Uso de bliotecas de terceiros

O Uso de bibliotecas de terceiros devem ser evitadasm nas caso sejam necessário, deverá ser acredico no README do exemplo detalhes de como obte-las, instala-las e como compilar o exemplo,  

# Código de Conduta 

## Nossa promessa

No interesse de promover um ambiente aberto e acolhedor, nós, como contribuintes e mantenedores, nos comprometemos a tornar a participação em nosso projeto e em nossa comunidade uma experiência livre de assédio para todos, independentemente da idade, tamanho do corpo, deficiência, etnia, identidade e expressão de gênero, nível de experiência, nacionalidade, aparência pessoal, raça, religião ou identidade e orientação sexual.

## Nossos Padrões

Exemplos de comportamento que contribui para a criação de um ambiente positivo incluem:

- Usar uma linguagem acolhedora e inclusiva
- Respeitar os diferentes pontos de vista e experiências
- Aceitando críticas construtivas com elegância
- Foco no que é melhor para a comunidade
- Mostrar empatia para com outros membros da comunidade

Exemplos de comportamento inaceitável por parte dos participantes incluem:

- Uso de linguagem ou imagens sexualizadas e atenção ou avanços sexuais indesejados
- Comentários de trollagem, insultos / depreciativos e ataques pessoais ou políticos
- Assédio público ou privado
- Publicar informações privadas de terceiros, como um endereço físico ou eletrônico, sem permissão explícita
- Outras condutas que poderia ser razoavelmente considerada inadequada em um ambiente profissional

## Nossas responsabilidades

Os mantenedores do projeto são responsáveis por esclarecer os padrões de comportamento aceitável e devem tomar as ações corretivas adequadas e justas em resposta a quaisquer instâncias de comportamento inaceitável.

Os mantenedores do projeto têm o direito e a responsabilidade de remover, editar ou rejeitar comentários, commits, códigos, edições de wiki, questões e outras contribuições que não estejam alinhadas a este Código de Conduta, ou banir temporária ou permanentemente qualquer contribuidor por outros comportamentos que eles consideram inadequados, ameaçadores, ofensivos ou prejudiciais.

## Escopo

Este Código de Conduta se aplica tanto aos espaços do projeto quanto aos espaços públicos quando um indivíduo está representando o projeto ou sua comunidade. Exemplos de representação de um projeto ou comunidade incluem o uso de um endereço de e-mail oficial do projeto, publicação por meio de uma conta oficial de mídia social ou atuação como representante indicado em um evento online ou offline. A representação de um projeto pode ser posteriormente definida e esclarecida pelos mantenedores do projeto.

## Execução

Casos de comportamento abusivo, de assédio ou de outra forma inaceitável podem ser relatados entrando em contato com a equipe do projeto em ricuinho@carlosdelfino.eti.br. Todas as reclamações serão analisadas e investigadas e resultarão em uma resposta considerada necessária e apropriada às circunstâncias. A equipe do projeto é obrigada a manter a confidencialidade em relação ao relator de um incidente. Mais detalhes de políticas de aplicação específicas podem ser publicados separadamente.

Os mantenedores do projeto que não seguem ou não aplicam o Código de Conduta de boa fé podem enfrentar represenções temporárias ou permanentes, conforme determinado por outros membros da liderança do projeto.

## Atribuição

Este Código de Conduta foi adaptado do Pacto do Colaborador, versão 1.4, disponível em http://contributor-covenant.org/version/1/4
