# cards

A Rust rewrite of [GsnailG](https://github.com/GsnailG)'s CaH [card extension website](https://gsnailg.github.io/cards).
This rewrite is written in Rust using the [Yew framework](https://yew.rs).

## Egui

I further [attempted to rewrite](https://github.com/hdert/cards-app) this website using [egui](https://www.egui.rs). This would've allowed me to deploy to the web and to desktop. This did not work out as the immediate mode gui was fundamentally incompatible with the layout and styling I wanted to use to try and replicate GsnailG's original website.

## Dioxus

After this I still wanted to try and deploy to desktop and potentially mobile along with web. For this I decided to try and use [Dioxus](https://dioxuslabs.com).

I haven't yet finished it but you can find it [here](https://github.com/hdert/cards-dioxus-app).