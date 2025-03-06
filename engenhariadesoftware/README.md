# AULA 01 (14/02/2025)

Crie um repositório chamado "bertoti" -> pasta "engenhariadesoftware" -> arquivo "readme.md" e faça as seguintes atividades:

1 - Comentar com suas palavras o primeiro trecho do livro Software Engineering at Google, Oreilly. 

2 - Comentar com suas palavras o segundo trecho do livro Software Engineering at Google, Oreilly.

3 - Listar e explicar 3 exemplos de tradeoffs

## ATIVIDADE 01

Programming Over Time
We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers.
 
One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation?
 
The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:
 
Time and Change
How code will need to adapt over the length of its life
 
Scale and Growth
How an organization will need to adapt as it evolves
 
Trade-offs and Costs
How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth

#### Comentário:

O trecho do livro Software Engineering at Google, Oreilly enfatiza que o desenvolvimento de software é um processo contínuo, ou seja, que necessita de manutenções ao longo do seu tempo de vida. É destacado os três princípios para que a contrução de um software seja eficiente:

- Time and Change (quando um código necessita ser adaptado?): -> o software tem que ser projetado de forma que ele possa ter manutenções de maneira inteligente.
- Scale and Growth (de que forma um software pode crescer de maneira sustentável?): -> À medida que um sistema e sua equipe crescem, processos precisam ser adaptados para garantir eficiência e colaboração. Arquiteturas escaláveis e boas práticas de engenharia são essenciais para acompanhar essa evolução. 
- Trade-offs and Costs (como as decisões de desenvolvimento impactam o projeto?) -> Cada escolha feita no desenvolvimento de software envolve compensações, como custo, tempo e qualidade. Tomar decisões equilibradas é essencial para garantir a sustentabilidade do sistema.

## ATIVIDADE 02

What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years?
 
The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.”
 
“Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create.
 
Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.

#### Comentário:

O trecho diferencia programação de engenharia de software, destacando que, embora ambos envolvam a escrita de código, a engenharia de software busca aplicar conhecimentos teóricos para criar sistemas confiáveis e escaláveis. Enquanto programadores muitas vezes focam na implementação de funcionalidades, engenheiros de software lidam com desafios maiores, como manutenção, escalabilidade e qualidade do código ao longo do tempo.

## ATIVIDADE 03

- Simplicidade x Funcionalidade -> Um software simples é mais fácil de entender e manter, mas pode não atender a todas as necessidades dos usuários. Já um software repleto de funcionalidades pode ser mais útil, porém mais complexo e difícil de manter.
- Escalabilidade x Custo -> Criar um sistema altamente escalável pode exigir investimentos iniciais elevados, enquanto uma solução mais barata pode não suportar um grande volume de usuários no futuro.
- Segurança x Facilidade de Uso -> Medidas de segurança rigorosas, como autenticação em múltiplos fatores, podem proteger os dados, mas podem tornar a experiência do usuário mais complexa. Uma interface simples e acessível pode comprometer a segurança.
