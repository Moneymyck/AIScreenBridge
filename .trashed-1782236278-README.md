# AI Screen Bridge

Application Android native Kotlin.

## Ce que fait cette version

- Lit le texte visible à l'écran via Android AccessibilityService.
- Affiche une bulle flottante "AI".
- Quand tu appuies sur la bulle, elle envoie le contexte écran à OpenAI ou Claude.
- Affiche la réponse IA en bas de l'écran.
- Masque certains éléments sensibles avant envoi.

## Ce que cette version ne fait pas encore

- Elle ne lit pas les images sans texte.
- Elle ne contourne pas les champs protégés.
- Elle ne clique pas automatiquement à ta place.
- Elle n'utilise pas encore MediaProjection/OCR.

## Installation

1. Ouvre le dossier dans Android Studio.
2. Build > Build APK.
3. Installe l'APK sur ton téléphone Android.
4. Ouvre l'app.
5. Autorise la bulle flottante.
6. Va dans Accessibilité > AI Screen Bridge > Activer.
7. Mets ta clé API OpenAI ou Anthropic.
8. Ouvre une autre application et appuie sur la bulle AI.

## Modèles conseillés

OpenAI:
- gpt-4.1-mini
- gpt-4.1

Claude:
- claude-sonnet-4-5
- claude-haiku-4-5

## Sécurité

Ne mets pas cette app sur le Play Store sans politique de confidentialité claire.
Une app Accessibilité peut voir beaucoup de texte affiché à l'écran.
