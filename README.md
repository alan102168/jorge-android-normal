# 📱 Jorge the Truck Driver — Android Normal

> **Este repositório contém somente o aplicativo Android com os gráficos normais.** A versão Pixel Art fica em outro repositório.

### ⬇️ Baixar o APK

**[Ver Releases do Android Normal](https://github.com/alan102168/jorge-android-normal/releases)**

1. Abra o Release mais recente com a identificação `android-normal`.
2. Toque no arquivo `app-debug.apk` (é um **APK de teste**, não uma publicação na Play Store).
3. Para instalar, siga as opções de instalação que seu Android mostrar.

Caso o Release não apareça, consulte [Actions](https://github.com/alan102168/jorge-android-normal/actions) → compilação concluída → *Artifacts*.

### 📁 Estrutura

- `app/src/main/assets/index.html` — motor do jogo HTML que roda dentro do Android.
- `app/src/main/java/br/com/jorgetruckdriver/android/MainActivity.java` — integração Android, tela e gamepad.
- `app/src/main/AndroidManifest.xml` — configuração do aplicativo.
- `app/build.gradle`, `build.gradle`, `settings.gradle` — compilação.
- `.github/workflows/android-apk.yml` — gera APK e publica Releases.

**Identificador Android:** `br.com.jorgetruckdriver.android`, diferente do Pixel Art. Os controles USB, Bluetooth e receptor dependem de reconhecimento pelo próprio aparelho.

### 🧪 Situação

O GitHub Actions gera o APK; **testes reais no celular, HDMI e controles ainda são necessários**. Não confundir compilação bem-sucedida com compatibilidade garantida.

### 📚 Outras versões

| Edição | Repositório |
|---|---|
| 🌐 HTML Normal | [Abrir](https://github.com/alan102168/jogo-sest-senat-2d-caminhao) |
| 🎨 HTML Pixel Art | [Abrir](https://github.com/alan102168/jorge-html-pixel) |
| 📱 Android Normal | [Abrir](https://github.com/alan102168/jorge-android-normal) |
| 📱 Android Pixel Art | [Abrir](https://github.com/alan102168/jorge-truck-driver-android) |
| 🎮 ROM Mega Drive Pixel Art | [Abrir](https://github.com/alan102168/jorge-megadrive-pixel) |
