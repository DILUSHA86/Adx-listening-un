# Adx-listening-un
Adx protocol 
/* 
   ADX-PROTOCOL PHASE 7: 3D NEURAL-LINK 
   Technology: Three.js / WebGL
*/
import * as THREE from 'three';

const scene = new THREE.Scene();
const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);

// Visualize the 1850000 Proton Sync as 3D Synapses
const geometry = new THREE.BufferGeometry();
const points = [];
for (let i = 0; i < 1850000; i++) {
    // Generate the cord field
    points.push(Math.random() * 2 - 1, Math.random() * 2 - 1, Math.random() * 2 - 1);
}
// Add 3D logic to your portfolio.html next...
