---
layout: home
title: PLUS HUB - The largest collection of high rated stuff on the internet
description: PLUS HUB offers the largest collection of free resources including movies, TV shows, anime, music, games, books, software, and more. Your ultimate guide to free content and entertainment.
keywords: free movies, free tv shows, free anime, free music, free games, free books, free software, streaming, downloading, torrenting, free resources, entertainment, media

hero:
  name: "PLUS HUB"
  text: ""
  tagline: The largest collection of high rated stuff on the internet!
  image:
    src: /assets/hero-play.svg
    alt: PLUS HUB
  actions:
    - theme: brand
      text: See Beginners Guide
      link: /beginners-guide
---


<div class="filter-bar">
  <button class="filter-btn active" data-filter="all">All</button>
  <button class="filter-btn" data-filter="movies">Movies</button>
  <button class="filter-btn" data-filter="anime">Anime</button>
  <button class="filter-btn" data-filter="manga">Manga</button>
  <button class="filter-btn" data-filter="embeds">Embeds</button>
  <button class="filter-btn" data-filter="live-sports">Live Sports</button>
  <button class="filter-btn" data-filter="live-tv">Live TV</button>
  <button class="filter-btn" data-filter="vpn">VPN</button>
  <button class="filter-btn" data-filter="paid">Paid</button>
  <button class="filter-btn" data-filter="apps">Apps</button>
</div>

<div id="content-container">
<div class="category-grid" id="category-grid">

<a href="/adblock-privacy" class="category-card">
  <div class="category-icon" style="--icon-color:#ff6b9d;">
    <i class="fa-solid fa-shield-halved"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Ad-block / Privacy</h3>
    <p class="category-desc">Learn how to block ads, trackers and other nasty things.</p>
  </div>
</a>

<a href="/artificial-intelligence" class="category-card">
  <div class="category-icon" style="--icon-color:#a78bfa;">
    <i class="fa-solid fa-robot"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Artificial Intelligence</h3>
    <p class="category-desc">Explore the world of AI and machine learning.</p>
  </div>
</a>

<a href="/streaming" class="category-card">
  <div class="category-icon" style="--icon-color:#60a5fa;">
    <i class="fa-solid fa-clapperboard"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Streaming</h3>
    <p class="category-desc">Stream, download, torrent and binge all your favourite movies and shows!</p>
  </div>
</a>

<a href="/audio" class="category-card">
  <div class="category-icon" style="--icon-color:#ba68c8;">
    <i class="fa-solid fa-headphones-simple"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Listening</h3>
    <p class="category-desc">Stream, download and torrent songs, podcasts and more!</p>
  </div>
</a>

<a href="/gaming" class="category-card">
  <div class="category-icon" style="--icon-color:#22d3ee;">
    <i class="fa-solid fa-gamepad"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Gaming</h3>
    <p class="category-desc">Download and play all your favourite games or emulate some old but gold ones!</p>
  </div>
</a>

<a href="/reading" class="category-card">
  <div class="category-icon" style="--icon-color:#34d399;">
    <i class="fa-solid fa-book-open"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Reading</h3>
    <p class="category-desc">Whether you're a bookworm, otaku or comic book fan, you'll find your favourite pieces of literature here!</p>
  </div>
</a>

<a href="/downloading" class="category-card">
  <div class="category-icon" style="--icon-color:#f59e0b;">
    <i class="fa-solid fa-download"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Downloading</h3>
    <p class="category-desc">Download all your favourite software, movies, shows, music, games and more!</p>
  </div>
</a>

<a href="/torrenting" class="category-card">
  <div class="category-icon" style="--icon-color:#c084fc;">
    <i class="fa-solid fa-magnet"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Torrenting</h3>
    <p class="category-desc">Download your favourite media using the BitTorrent protocol.</p>
  </div>
</a>

<a href="/educational" class="category-card">
  <div class="category-icon" style="--icon-color:#3b82f6;">
    <i class="fa-solid fa-graduation-cap"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Educational</h3>
    <p class="category-desc">Educational content for all ages.</p>
  </div>
</a>

<a href="/android-ios" class="category-card">
  <div class="category-icon" style="--icon-color:#10b981;">
    <i class="fa-solid fa-mobile-screen-button"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Android / iOS</h3>
    <p class="category-desc">All forms of content for Android and iOS.</p>
  </div>
</a>

<a href="/linux-macos" class="category-card">
  <div class="category-icon" style="--icon-color:#f97316;">
    <i class="fa-solid fa-terminal"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Linux / macOS</h3>
    <p class="category-desc">The $HOME of Linux and macOS.</p>
  </div>
</a>

<a href="/non-english" class="category-card">
  <div class="category-icon" style="--icon-color:#ef4444;">
    <i class="fa-solid fa-language"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Non-English</h3>
    <p class="category-desc">Content in languages other than English.</p>
  </div>
</a>

<a href="/miscellaneous" class="category-card">
  <div class="category-icon" style="--icon-color:#eab308;">
    <i class="fa-solid fa-shapes"></i>
  </div>
  <div class="category-content">
    <h3 class="category-title">Miscellaneous</h3>
    <p class="category-desc">Various topics like food, travel, news, shopping, fun sites and more!</p>
  </div>
</a>

</div>
</div>

<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  // Add Font Awesome if not already loaded
  if (!document.querySelector('link[href*="font-awesome"]')) {
    const link = document.createElement('link')
    link.rel = 'stylesheet'
    link.href = 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css'
    document.head.appendChild(link)
  }

  // Filter data - content for each filter
  const filterData = {
    all: null, // Will show default category grid
    movies: {
      title: '| Movies & Series |',
      subFilters: ['All', 'Hollywood', 'Indian', 'French', 'Portuguese'],
      items: [
        { name: 'Hotflix', logo: 'https://hotflix.su/logo.png', url: 'https://hotflix.su', subFilter: 'Hollywood' },
        { name: 'Vidbox', logo: 'https://vidbox.cc/logo.png', url: 'https://vidbox.cc', subFilter: ['Hollywood', 'Indian'] },
        { name: 'CineHD', logo: 'https://cinehd.cc/logo.png', url: 'https://cinehd.cc', subFilter: 'Indian' },
        { name: 'Autoembed', logo: 'https://autoembed.cc/images/logo.png?v=0.6', url: 'https://watch.autoembed.cc', subFilter: 'Indian' },
        { name: 'Primeshows', logo: '/assets/primeshows/logo.png', url: 'https://primeshows.live', subFilter: 'Hollywood' },
        
        { name: 'Smashystream', logo: 'https://tbcpl.lol/logo/movies_shows/smashystream.png', url: 'https://smashystream.xyz/' }
      ]
    },
    anime: {
      title: '| Anime |',
      subFilters: ['All', 'Sub', 'Dub', 'Donghua'],
      items: [
        { name: 'Hotflix', logo: 'https://hotflix.su/logo.png', url: 'https://hotflix.su', subFilter: 'Sub' },
        { name: 'Vidbox', logo: 'https://vidbox.cc/logo.png', url: 'https://vidbox.cc', subFilter: ['Sub', 'Dub'] },
        { name: 'CineHD', logo: 'https://cinehd.cc/logo.png', url: 'https://cinehd.cc', subFilter: 'Dub' },
        { name: 'Autoembed', logo: 'https://autoembed.cc/images/logo.png?v=0.6', url: 'https://watch.autoembed.cc', subFilter: 'Sub' },
        { name: 'Primeshows', logo: '/assets/primeshows/logo.png', url: 'https://primeshows.live', subFilter: 'Dub' },
        { name: 'Smashystream', logo: 'https://tbcpl.lol/logo/movies_shows/smashystream.png', url: 'https://smashystream.xyz/', subFilter: 'Donghua' }
      ]
    },
    manga: {
      title: '| Manga |',
      items: [
        { name: 'Hotflix', logo: 'https://hotflix.su/logo.png', url: 'https://hotflix.su' },
        { name: 'Vidbox', logo: 'https://vidbox.cc/logo.png', url: 'https://vidbox.cc' },
        { name: 'CineHD', logo: 'https://cinehd.cc/logo.png', url: 'https://cinehd.cc' },
        { name: 'Autoembed', logo: 'https://autoembed.cc/images/logo.png?v=0.6', url: 'https://watch.autoembed.cc' },
        { name: 'Primeshows', logo: '/assets/primeshows/logo.png', url: 'https://primeshows.live' },
        { name: 'Smashystream', logo: 'https://tbcpl.lol/logo/movies_shows/smashystream.png', url: 'https://smashystream.xyz/' }
      ]
    },
    embeds: {
      title: '| Embeds |',
      subFilters: ['All', 'Movies', 'TV Shows', 'Anime'],
      items: [
        { name: 'Hotflix', logo: 'https://hotflix.su/logo.png', url: 'https://hotflix.su', subFilter: 'Movies' },
        { name: 'Vidbox', logo: 'https://vidbox.cc/logo.png', url: 'https://vidbox.cc', subFilter: ['Movies', 'TV Shows'] },
        { name: 'CineHD', logo: 'https://cinehd.cc/logo.png', url: 'https://cinehd.cc', subFilter: 'TV Shows' },
        { name: 'Autoembed', logo: 'https://autoembed.cc/images/logo.png?v=0.6', url: 'https://watch.autoembed.cc', subFilter: 'Movies' },
        { name: 'Primeshows', logo: '/assets/primeshows/logo.png', url: 'https://primeshows.live', subFilter: 'Anime' },
        { name: 'Smashystream', logo: 'https://tbcpl.lol/logo/movies_shows/smashystream.png', url: 'https://smashystream.xyz/', subFilter: 'TV Shows' }
      ]
    },
    'live-sports': { title: '| Live Sports |', items: [] },
    'live-tv': { title: '| Live TV |', items: [] },
    vpn: { title: '| VPN |', items: [] },
    paid: { title: '| Paid Services |', items: [] },
    apps: { title: '| Apps |', items: [] }
  }

  // Function to render streaming services grid with sub-filters
  function renderStreamingGrid(data, selectedSubFilter = 'All') {
    const container = document.getElementById('content-container')
    if (!container) return

    let html = `<h2 class="filter-title">${data.title}</h2>`
    
    // Add sub-filter bar if subFilters exist
    if (data.subFilters && data.subFilters.length > 0) {
      html += '<div class="sub-filter-bar">'
      data.subFilters.forEach(subFilter => {
        const isActive = subFilter === selectedSubFilter
        html += `<button class="sub-filter-btn ${isActive ? 'active' : ''}" data-sub-filter="${subFilter}">${subFilter}</button>`
      })
      html += '</div>'
    }
    
    // Filter items based on selected sub-filter
    const filteredItems = data.items.filter(item => {
      if (selectedSubFilter === 'All') {
        // Show all items when "All" is selected
        return true
      }
      // Handle array subFilter (e.g., ['Hollywood', 'Indian'])
      if (Array.isArray(item.subFilter)) {
        return item.subFilter.includes(selectedSubFilter)
      }
      // Show items that match the selected sub-filter OR have subFilter: 'All'
      // Items without subFilter property are excluded when a specific sub-filter is selected
      return item.subFilter === selectedSubFilter || item.subFilter === 'All'
    })
    
    if (filteredItems.length === 0) {
      // Show message when no items match the filter
      html += '<p style="text-align: center; color: var(--vp-c-text-2); margin: 2rem 0;">Coming soon</p>'
    } else {
      html += '<div class="streaming-grid">'
      
      filteredItems.forEach(item => {
        // Create link with no-referrer and new window - logo only, no text
        html += `
          <a href="${item.url}" target="_blank" rel="noopener noreferrer" class="streaming-item" title="${item.name}">
            <img src="${item.logo}" alt="" referrerpolicy="no-referrer">
          </a>
        `
      })
      
      html += '</div>'
    }
    container.innerHTML = html
    
    // Attach sub-filter button event listeners
    if (data.subFilters && data.subFilters.length > 0) {
      const subFilterButtons = container.querySelectorAll('.sub-filter-btn')
      subFilterButtons.forEach(btn => {
        btn.addEventListener('click', () => {
          const subFilter = btn.getAttribute('data-sub-filter')
          renderStreamingGrid(data, subFilter)
        })
      })
    }
  }

  // Function to show default category grid
  function showDefaultGrid() {
    const container = document.getElementById('content-container')
    const defaultGrid = document.getElementById('category-grid')
    if (container && defaultGrid) {
      container.innerHTML = defaultGrid.outerHTML
    }
  }

  // Filter bar functionality
  const filterButtons = document.querySelectorAll('.filter-btn')
  const container = document.getElementById('content-container')
  const defaultGrid = document.getElementById('category-grid')
  
  // Save the default grid HTML
  let defaultGridHTML = defaultGrid ? defaultGrid.outerHTML : ''

  filterButtons.forEach(btn => {
    btn.addEventListener('click', () => {
      // Remove active class from all buttons
      filterButtons.forEach(b => b.classList.remove('active'))
      // Add active class to clicked button
      btn.classList.add('active')
      
      const filter = btn.getAttribute('data-filter')
      
      if (!container) return
      
      if (filter === 'all') {
        // Show default category grid
        if (defaultGridHTML) {
          container.innerHTML = defaultGridHTML
          // Re-initialize the grid after restoring
          const restoredGrid = document.getElementById('category-grid')
          if (restoredGrid) {
            // Grid is restored, no action needed
          }
        }
      } else if (filterData[filter] && filterData[filter].items.length > 0) {
        // Render streaming services grid
        renderStreamingGrid(filterData[filter])
      } else {
        // Show empty state
        container.innerHTML = `<h2 class="filter-title">| ${filter.charAt(0).toUpperCase() + filter.slice(1).replace('-', ' ')} |</h2><p style="text-align: center; color: var(--vp-c-text-2); margin: 2rem 0;">Coming soon</p>`
      }
    })
  })
})
</script>
