# Checklist de risco jurídico para software (Brasil)

Aplicar antes de publicar, distribuir ou vender qualquer software, meu ou em parceria. Não substitui advogado: serve para achar o que falta e decidir o que precisa de revisão jurídica.

Regra de uso: item que não puder ser confirmado é marcado **"não verificado"**, nunca assumido como OK.

## 1. Documentos

1. Política de privacidade, Termos de uso/EULA e política de reembolso publicados e coerentes com o que o software realmente faz.
2. Aviso de cookies e consentimento prévio para scripts de tracking/analytics não essenciais.

## 2. Dados pessoais e dados de terceiros (LGPD)

3. Coletar só dados necessários, com base legal definida, formulário claro e canal para o titular exercer seus direitos. Cuidado extra com dados de crianças e dados sensíveis.
4. Dados de clientes e de terceiros nunca podem vazar nem ser acessados por quem não tem autorização:
   - controle de acesso por menor privilégio; um cliente nunca enxerga dados de outro;
   - criptografia em trânsito (HTTPS/TLS) e dados sensíveis criptografados em repouso;
   - segredos (chaves, senhas, tokens) fora do código e do repositório, e nunca em logs;
   - dados reais de clientes nunca em ambiente de teste, em prompts de IA ou em serviços de terceiros sem contrato e base legal;
   - lista de operadores e subprocessadores (hospedagem, analytics, IA, pagamento) com contrato adequado;
   - prazo de retenção definido e exclusão quando o dado deixa de ser necessário;
   - plano de resposta a incidente, incluindo comunicação à ANPD e aos titulares quando houver risco relevante.

## 3. Venda

5. Identificação do fornecedor visível (razão social, CNPJ, endereço, contato).
6. Venda online ao consumidor: preço total e condições claros antes da compra, e direito de arrependimento de 7 dias (CDC, art. 49).
7. Publicidade honesta: sem avaliações, depoimentos ou números falsos, e sem promessas que o software não cumpre.
8. Regularidade fiscal: nota fiscal e enquadramento tributário corretos.

## 4. Propriedade intelectual

9. Licenças de todas as dependências e códigos de terceiros, com compatibilidade para venda ou distribuição fechada. Atenção a GPL/AGPL (copyleft).
10. Código, imagens, fontes, ícones e modelos de terceiros ou gerados por IA: confirmar o direito de uso e distribuição e guardar a prova da origem. A autoria de código gerado por IA tem incerteza jurídica real; levar a advogado.
11. Marcas e nomes: checar conflito antes de lançar.

## 5. Segurança e qualidade

12. Dependências sem vulnerabilidades conhecidas e atualizadas; autenticação e validação de entrada revisadas.
13. Acessibilidade: contraste, texto alternativo em imagens e navegação por teclado.

## 6. Verificação final

14. Revisar todos os itens acima antes de cada publicação e a cada mudança relevante.

## Origem

Baseado em uma lista de 17 itens de um vídeo sobre sites feitos com IA, com redundâncias removidas e itens de software, venda e proteção de dados de terceiros acrescentados.
