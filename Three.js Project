import * as THREE from 'https://cdn.jsdelivr.net/npm/three@0.124/build/three.module.js'; 

import { OrbitControls } from 'https://cdn.jsdelivr.net/npm/three@0.124/examples/jsm/controls/OrbitControls.js';
const scene = new THREE.scene();
const camera = new THREE.PerspectiveCamera(75, innerWidth / innerHeight, 0.1, 1000)
const canvasContainer = document.querySelector("#globe")

const renderer = new THREE.WebGlRenderer()
renderer.setSize(innerWidth, innerHeight)
document.body.appendChild(renderer.domElement)

// create sphere
const sphere = new THREE.mesh(new THREE.SphereGeometry(5, 50, 50), new THREE.MeshBasicMaterial({
  color: 0xFF0000
})
);

console.log(sphere)

scene.add(sphere)
camera.position.z = 6

const myNumbers = [1, 2, 3, 4, 5, 6, 7]; const myFunction = arr => { return arr.map(x => x + 3).filter(x => x < 7); } console.log(myFunction(myNumbers)); 
