<script lang="ts">
	import { Canvas } from '@threlte/core';

	import { T } from '@threlte/core';
    import { Environment, OrbitControls } from '@threlte/extras'
	import Watch from './Watch.svelte';

</script>
<div style="height: 100vh;">
    <Canvas>
        <Environment
        files="watch_env.hdr"
        isBackground={true}        
      />
      <T.PerspectiveCamera
        makeDefault
        position={[1, 1, 1]}
        fov={85}
      >
        <OrbitControls
        
          enableDamping
        />
      </T.PerspectiveCamera>
      <T.AmbientLight />
      <Watch></Watch>

    </Canvas>
    
</div>
