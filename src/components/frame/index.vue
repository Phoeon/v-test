<template>
	<div id="frame">
		<slot name="frame-header">
			<FrameHeader></FrameHeader>
		</slot>
		<slot name="frame-body">
			<main class="frame-body">
				<slot name="frame-sidebar">
					<div class="frame-sidebar">frame-sidebar</div>
				</slot>
				<slot name="frame-main">
					<div class="frame-main">frame-main</div>
				</slot>
			</main>
		</slot>
		<slot name="frame-footer">
			<footer class="frame-footer">frame-footer</footer>
		</slot>
	</div>
</template>
<script>
import FrameHeader from './frame-header';
export default {
	name : "frame",
	components : {FrameHeader}
}
</script>
<style name="scoped">

</style>