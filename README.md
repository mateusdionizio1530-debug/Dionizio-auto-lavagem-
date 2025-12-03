# Dionizio Auto Lavagem - Projeto Flutter (completo - placeholders)

Gerado em: 2025-12-03T14:34:46.572367Z

Esse repositório contém o projeto base finalizado com suas configurações:
- Horário de funcionamento: 08:00 às 17:00
- Capacidade diária: máximo 10 carros
- PIX key configurada por CPF: 13287562460 (substitua se necessário)
- Serviços adicionados (com preços e durações sugeridas):
  - Lavagem simples — R$30 — 30 min
  - Lavagem com polimento — R$80 — 60 min
  - Lavagem premium — R$120 — 90 min
  - Higienização interna — R$150 — 60 min
  - Polimento manual — R$200 — 120 min
  - Lavagem de motor — R$70 — 45 min
  - Detalhamento de chassi — R$180 — 150 min

## Como usar
1. Abra no Android Studio ou VS Code.
2. Rode `flutter pub get`.
3. Configure Firebase (opcional) e coloque as credenciais em `android/app/google-services.json` e `ios/GoogleService-Info.plist`.
4. Substitua as chaves em `lib/services/payment_service.dart`.
5. Para integração real de cartão, implemente uma Cloud Function / servidor para criar `PaymentIntent` com a chave secreta Stripe.
6. Para PIX via gateway, configure a URL do gateway e as chaves.
7. Build:
   - Debug: `flutter run`
   - Build APK: `flutter build apk --release`
   - Build iOS: abra Xcode em `ios/Runner.xcworkspace` e configure as assinaturas.

## Próximos passos que posso realizar para você:
- Integrar Firebase Auth (telefone SMS + e-mail) e Firestore com regras.
- Implementar Cloud Functions para pagamentos e automações.
- Desenvolver painel admin em React e publicar em Firebase Hosting.
- Gerar APK e IPA (builds) e instruções passo-a-passo.
- Ajustar preços, horários e capacidade conforme necessidade.

