<script>
  import Ota from "./components/OTA.svelte";
  import LocalNotifications from "./components/LocalNotifications.svelte";
  import TTS from "./components/TTS.svelte";
  import Camera from "./components/Camera.svelte";
  import DeviceOrientation from "./components/DeviceOrientation.svelte";
  import OpenAndroidApp from "./components/OpenAndroidApp.svelte";
  import Toast from "./components/Toast.svelte";
  import Dialog from "./components/Dialog.svelte";
  import Clipboard from "./components/Clipboard.svelte";
  import InAppBrowser from "./components/InAppBrowser.svelte";
  import ConfettiExplosion from "./components/ConfettiExplosion.svelte";
  import BackButton from "./components/BackButton.svelte";
  import ExitApp from "./components/ExitApp.svelte";
  import InstallApk from "./components/InstallApk.svelte";
  import NetworkCheck from "./components/NetworkCheck.svelte";
  import PdfViewer from "./components/PdfViewer.svelte";
  import PinchToZoom from "./components/PinchToZoom.svelte";
  import DeviceType from "./components/DeviceType.svelte";
  import StatusBar from "./components/StatusBar.svelte";
  import IsAndroid from "./components/IsAndroid.svelte";
  import AppState from "./components/AppState.svelte";
  import PdfRenderer from "./components/PdfRenderer.svelte";
  import KeyBoard from "./components/KeyBoard.svelte";
  import NavigationBar from "./components/NavigationBar.svelte";
</script>

<main class="container">
  <LocalNotifications />
  <TTS />
  <Camera />
  <DeviceOrientation />
  <OpenAndroidApp />
  <Toast />
  <Dialog />
  <Clipboard />
  <InAppBrowser />
  <ConfettiExplosion />
  <BackButton />
  <ExitApp />
  <InstallApk />
  <NetworkCheck />
  <PdfViewer />
  <PinchToZoom />
  <DeviceType />
  <StatusBar />
  <IsAndroid />
  <Ota />
  <!-- <AppState /> -->
  <!-- <PdfRenderer path="/book.pdf"/> -->
  <KeyBoard/>
  <NavigationBar/>
</main>

<style>
</style>
