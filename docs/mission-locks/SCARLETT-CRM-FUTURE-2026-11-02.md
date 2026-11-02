# Scarlett Clinic Prime — Proposta futura de CRM e automações (não executada)

> **MISSÃO PROPOSTA, NÃO ATIVADA | 2026-11-02.** Este arquivo está no fork LeadsDeskCRM **somente como referência de integração** porque NÃO foi identificado um repositório exclusivo e comprovadamente canônico do software Scarlett entre os repositórios atualmente acessíveis. **Isto não é o Mission Lock do runtime da Scarlett.** Não implantar nem importar dados reais a partir deste documento.

## Missão quando houver fonte canônica

1. Inventariar plugin/aplicação ativa, banco, usuários e contratos de agenda com backup/restauração de teste; antes disso, **NO-GO**.
2. Consultar com equipe clínica e comercial as regras de acolhimento, agendamento, confirmação, não comparecimento, pós-atendimento, retorno, preços aprovados e preferências de comunicação.
3. Examinar, em **sandbox com dados totalmente sintéticos**, módulos Deskcomm: `lib/inbox/`, `lib/agenda/`, `lib/followup/`, `lib/opt-out/`, `lib/crm-b2b/` (se realmente necessário), `lib/automation/`. Avaliar também modelos simples do CRM do Corretor.
4. Separar dados estritamente comerciais de **dados pessoais sensíveis de saúde**, anamnese, fotografias, consentimentos clínicos e procedimentos. Não transferir conteúdo clínico para modelo de IA, ferramenta externa, CRM genérico ou logs sem base, controles e aprovação específica. Recepção nunca recebe acesso clínico por conveniência.
5. Simular duas pacientes fictícias, papéis recepção/gestão/profissional, horários concorrentes, opt-out, transferência de atendimento, reenvio de webhook, arquivo privado, auditoria e reversão.
6. Não permitir inferências de diagnóstico, resultados garantidos, manipulação de insegurança corporal, precificação inventada ou campanhas automáticas com informação clínica.

## Fonte de verdade e escopo

- **Scarlett canônica: A IDENTIFICAR.** Deskcomm não assume identidade nem banco da clínica.
- O valor de avaliação mencionado em documentos de treinamento deve ser confirmado pela gestão e revisão de conformidade antes de configurar pagamento.
- A integração deve ser opt-in, minimizada, documentada e reversível, com versão congelada, autor e aprovação humana.

## Skills, evidência e status

ECP (planejamento/STOP), COLISEUM (red team), ASE (contrato), CyberSec (LGPD e autorização), Wiring (sincronismo), Software Intelligence OS (testes), UI-X + Browser Director (fluxo de atendimento), TraceProof (proveniência). **Status: PROPOSED / NO_RUNTIME_ACCESS / NOT_VERIFIED / NO_GO_PRODUCTION.**

## Referências

- [DeskcommCRM original](https://github.com/melgarafael/DeskcommCRM) / [LeadsDeskCRM fork](https://github.com/Suamarcanotopo/LeadsDeskCRM).
- Manual Comercial Consultivo v4.0 (documento Scarlett existente; código, dados e plugin não verificados aqui).
