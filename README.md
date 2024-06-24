# links-ginnastica
Una serie di link per fare ginnastica

<script>
  class LinksComponent extends HTMLElement {
  constructor() {
    super();
    this.attachShadow({ mode: 'open' });
  }

  connectedCallback() {
    this.render();
  }

  render() {
    const name = this.getAttribute('name') || '';
    const frag = this.getAttribute('frag') || '';
    const sites = ['site1', 'site2']; // Add more sites as needed

    const links = sites.map(site => `
      <a href="${site}/${frag}">${name} ${site}</a>
    `).join('');

    this.shadowRoot.innerHTML = `
      <style>
        :host {
          display: block;
        }
        a {
          margin-right: 10px;
        }
      </style>
      <div>${links}</div>
    `;
  }
}

customElements.define('links-component', LinksComponent);
</script>


 <links-component name="pippo" frag="1234"></links-component>

  <links-component name="pluto" frag="3456"></links-component>


# Spinning

## 30

- https://www.youtube.com/watch?v=KxoNVXnCUTQ Best 35'

## 45'

- https://www.youtube.com/watch?v=zSFYRiqodvU  CTXT
- 


# Video

## Musica

- https://www.youtube.com/watch?v=YM9iMubSmbI synth britannia
- https://www.youtube.com/watch?v=RWKfV7jbUJE psychedelic britannia
- https://www.youtube.com/watch?v=LyYaWD3DWIU
- https://www.youtube.com/watch?v=QyfzyS1CAaw  DMode 81/82  



## Link misti

Spining

- https://www.youtube.com/@gcn
- https://www.youtube.com/@CTXCvideos
- https://www.youtube.com/@bestcycling_oficial - lista https://www.youtube.com/watch?v=QsS8Pj4n0So&list=PLFrb2djd0eeZ-I2jGiKb3RFAh5SOb8WIU

Playlist musica elettronica

- https://www.youtube.com/playlist?list=PL9IOjFRFjrOlaSN20n8BVup9Sw5pECF_N
- 

Ralph supermaxieroe

- https://invidious.fi/playlist?list=PLtbMv4lXX2mvVYagk6BgBnNsr6VH0KUmG

- 
