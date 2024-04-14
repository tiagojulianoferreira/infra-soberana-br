# Infraestrutura Popular, Soberana e Distribuída de Serviços Digitais
Este repositório traz anotações preliminares visando identificar as possibilidades e desafios da especificação de uma infraestrutura soberana e distribuída de serviços digitais, baseada em hardware (prefenrencialmente) e software abertos, auto-hospedados para cenários residenciais e para movimentos sociais.

## Justificativa
- Iniciativas populares de provimento de serviços digitais baseados em software livre esbarram em gargalos ligados aos custos e dificuldade de acesso a infraestrutura
- Evitar a dependência por soluções "gratuitas" das bigtechs
## Objetivos
- Garantir autonomia total aos movimentos e/ou incentivar parcerias com profissionais locais
- Articular as carreiras de TI aos movimentos populares, com a visão do *trabalho como princípio educativo*

## Requisitos mandatórios
- A pilha de tecnologias de software deve ser baseada em software livre ou de código aberto.
- Os recursos de software devem buscar adequação aos protolocos de rede decentralizadas como [ActivetyPub](https://activitypub.rocks/)
- A instalação deve ser simplificada e auto-explicativa

## Requisitos desejáveis
- O hardware, preferencialmente, deve ser construído nacionalmente usando arquiterar abertas (OPH)
- O hardware deve buscar baixo consumo de energia
- A operação, nos níveis mais especializados, deve permitir o uso de infraestrutura como código

## Projetos de referêcia

| Tecnologia| Descrição | Recursos|
| ----------| --------- | ------- |
|[Subutai OptDyn](https://subutai.io/p2p-cloud-platform.html)| O projeto Subutai parece ser o caminho fácil já que, além de prover toda um console de gerenciamento da nuvem p2p, disponibiliza um hardware próprio, ou seja, uma infraestrutura que implementa os nós da rede localmente e de forma simples, o que poderia dar maior autonomia para o projeto. Ponto fraco: está na mão de uma startup estadunidense e acho um pouco obscura as informações.| Computação, Armazenamento |
| [IPFS](https://ipfs.tech/) |Nossa rede de entrega de conteúdo ponto a ponto é construída em torno da inovação do endereçamento de conteúdo: armazenar, recuperar e localizar dados com base na impressão digital de seu conteúdo real, e não em seu nome ou localização.| Armazenamento p2p |
| [Padrão RISC-V](https://riscv.org/) | A RISC-V International compreende uma grande organização membro que constrói a primeira comunidade aberta e colaborativa de inovadores de software e hardware que impulsionam a inovação na vanguarda. Através de vários eventos e workshops, a RISC-V International está a mudar a forma como a indústria trabalha em conjunto e colabora – criando um novo tipo de ecossistema aberto de hardware e software. Torne-se um membro hoje e ajude a ser pioneiro no futuro ISA de fato do setor para inovação em design. | Padrões abertos de HW |
| [Bacalhau](https://www.bacalhau.org/) |Bacalhau é uma plataforma de computação rápida, econômica e segura que permite aos usuários executar trabalhos de computação onde os dados são gerados e armazenados. | Computação, Computer Over Data, WebAssembly (WASM)|

