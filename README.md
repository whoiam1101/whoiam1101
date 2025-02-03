
      <svg
        width="300"
        height="165"
        viewBox="0 0 300 165"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #434d58;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .bold { font-weight: 700 }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #434d58;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
      /* Animations */
      @keyframes scaleInAnimation {
        from {
          transform: translate(-5px, 5px) scale(0);
        }
        to {
          transform: translate(-5px, 5px) scale(1);
        }
      }
      @keyframes fadeInAnimation {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#fffefe"
          stroke-opacity="1"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >Most Used Languages</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <svg data-testid="lang-items" x="25">
      
  
      <mask id="rect-mask">
          <rect x="0" y="0" width="250" height="8" fill="white" rx="5"/>
        </mask>
        
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="0"
          y="0"
          width="191.8"
          height="8"
          fill="#f34b7d"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="191.8"
          y="0"
          width="39.75"
          height="8"
          fill="#3572A5"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="231.55"
          y="0"
          width="15.59"
          height="8"
          fill="#89e051"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="247.14000000000001"
          y="0"
          width="11.76"
          height="8"
          fill="#dea584"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="248.9"
          y="0"
          width="10.64"
          height="8"
          fill="#555555"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.54"
          y="0"
          width="10.46"
          height="8"
          fill="#427819"
        />
      
      
    <g transform="translate(0, 25)">
      <g transform="translate(0, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#f34b7d" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        C++ 76.72%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#3572A5" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Python 15.90%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#89e051" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Shell 6.24%
      </text>
    </g>
  </g></g><g transform="translate(150, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#dea584" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Rust 0.71%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#555555" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        C 0.26%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#427819" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Makefile 0.18%
      </text>
    </g>
  </g></g>
    </g>
  
    </svg>
  
        </g>
      </svg>
    