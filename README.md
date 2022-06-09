# particles live https://jibon87.github.io/particles/

```
particles-js

1.  js--link ---> jquery.min.js

1.  js--link ---> js/particles.min.js

2.  css--link ---> css/style.css [

                /* particlesJS */
            #particles-js {
                position: absolute;
                width: 100%;
                height: 100%;
                /* background-color: #6819b652; */
                background-image: url("../img/slider-4.jpg");
                background-repeat: no-repeat;
                background-size: cover;
                background-position: 50% 50%;
            } 

]

3.  html 
    {
        <div id="particles-js"></div>

    }
    
4.  active js {

     // js particlesJS
    particlesJS("particles-js", {
        particles: {
            number: { value: 100, density: { enable: true, value_area: 800 } },
            color: { value: "#ffffff" },
            shape: { type: "triangle", stroke: { width: 1, color: "#ffffff" }, polygon: { nb_sides: 10 }, image: { src: "img/github.svg", width: 100, height: 100 } },
            opacity: { value: 0.5, random: false, anim: { enable: false, speed: 1, opacity_min: 0.1, sync: false } },
            size: { value: 3, random: true, anim: { enable: false, speed: 40, size_min: 0.1, sync: false } },
            line_linked: { enable: true, distance: 150, color: "#ffffff", opacity: 0.4, width: 2 },
            move: { enable: true, speed: 6, direction: "none", random: false, straight: false, out_mode: "out", bounce: false, attract: { enable: false, rotateX: 600, rotateY: 1200 } },
        },
        interactivity: {
            detect_on: "canvas",
            events: { onhover: { enable: true, mode: "repulse" }, onclick: { enable: true, mode: "push" }, resize: true },
            modes: {
                grab: { distance: 400, line_linked: { opacity: 1 } },
                bubble: { distance: 400, size: 40, duration: 2, opacity: 8, speed: 3 },
                repulse: { distance: 80, duration: 0.4 },
                push: { particles_nb: 4 },
                remove: { particles_nb: 2 },
            },
        },
        retina_detect: true,
    });
}
5.  note [ 
           
         ]
