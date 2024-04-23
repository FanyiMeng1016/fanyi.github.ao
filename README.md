# fanyi.github.ao
html,
body {
  margin: 0;
  padding: 0;
  background-color: white;
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
  left: 0;
  right: 0;
  width: auto;
}

/* This is a hack for FireFox that the <b> tag does not work */
strong,
b {
  font-weight: bold;
}

a {
  outline: none;
  cursor: pointer;
}

img {
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

video {
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

h2 {
  font-size: 24px;
  color: #333333;
  margin: 30px 0 0 0;
  padding: 0;
  font-weight: bold;
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
}

h3 {
  font-size: 18px;
  color: #333333;
  margin: 10px 0 0 0;
  padding: 0;
  font-weight: bold;
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
}

ul,
ol {
  margin: 10px 0 10px 0;
}

li ol,
li ul {
  margin: 0;
}

hr {
  border: 0;
  height: 1px;
  background: rgb(220, 220, 220);
  margin: 0 0 10px 0;
}

.menu-container {
  z-index: 2;
  position: relative;
  width: 100%;
  background-color: #333333;
  min-width: 300px;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  box-shadow: 0 0px 4px rgb(0 0 0 / 32%), 0 0px 10px rgb(0 0 0 / 23%);
}

.menu {
  position: relative;
  margin: 0 auto;
  max-width: 900px;
}

.menu .menu-table {
  padding: 0px 10px;
  width: 100%;
  margin: 0;
}

.menu .menu-highlight {
  color: rgb(255, 255, 255) !important;
  opacity: 1 !important;
  font-weight: 700 !important;
}

.menu .logo {
  margin-left: 20px;
}

.menu .logo a {
  color: rgba(255, 255, 255, 0.8);
  font-family: 'Open Sans Condensed', Helvetica, Arial, sans-serif;
  font-size: 30px;
  text-decoration: none;
  font-weight: 700;
  flex: 1 auto;
  padding: 10px 0;
}

.menu .logo a:hover {
  cursor: pointer;
}

.menu .logo img {
  margin: 0;
  padding: 0;
}

.menu .menu-button {
  width: 40px;
  height: 40px;
  display: none;
  cursor: pointer;
  margin-right: 20px;
}

.menu .menu-button img {
  width: 30px;
  height: 30px;
}

.menu .menu-items {
  align-self: stretch;
}

.menu .menu-items>a,
.menu .menu-items>div {
  color: rgba(255, 255, 255, 0.8);
  text-decoration: none;
  font-weight: 400;
  font-size: 18px;
  flex: 1 auto;
  transition: opacity 0.1s ease-in-out;
  -moz-transition: opacity 0.1s ease-in-out;
  -webkit-transition: opacity 0.1s ease-in-out;
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
  white-space: nowrap;
  display: flex;
  align-items: center;
  height: 100%;
}

.menu .menu-items>a:not(:last-child),
.menu .menu-items>div:not(:last-child) {
  margin-right: 25px;
}

.menu .menu-items>a:hover,
.menu .menu-items>div:hover {
  color: rgb(255, 255, 255);
  opacity: 1;
  cursor: pointer;
}

.menu .menu-items .dropdown {
  overflow: hidden;
  cursor: pointer;
}

.menu .menu-items .dropdown .dropbtn {
  font-family: inherit;
  text-decoration: inherit;
  color: inherit;
  font-weight: inherit;
  font-size: inherit;
  transition: inherit;
  -moz-transition: inherit;
  -webkit-transition: inherit;
  white-space: inherit;
  display: flex;
  align-items: center;
  height: 100%;
}

.menu .menu-items .dropdown i {
  color: #ffffff;
  margin-left: 5px;
}

.menu .menu-items .dropdown .dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 100px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  top: 100%;
  border-top: 3px solid #848484;
  border-bottom-left-radius: 2px;
  border-bottom-right-radius: 2px;
}

.menu .menu-items .dropdown .dropdown-content a {
  color: black;
  padding: 10px 20px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.menu .menu-items .dropdown .dropdown-content a:hover {
  background-color: #ddd;
  color: black;
}

.menu .menu-items .dropdown .dropdown-content a:last-child:hover {
  border-bottom-left-radius: 2px;
  border-bottom-right-radius: 2px;
}

.menu .menu-items .dropdown:hover .dropdown-content {
  display: block;
}

.content-container {
  z-index: 1;
  position: relative;
  width: 100%;
  min-width: 300px;
}

.content {
  position: relative;
  margin: 0 auto;
  font-size: 16px;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  font-weight: 300;
  line-height: 1.5;
  max-width: 900px;
  overflow-x: auto;
}

.content p a,
.content ul a,
.content ol a {
  text-decoration: none;
  color: #005cbf;
}

.content p a:hover,
.content ul a:hover,
.content ol a:hover {
  text-decoration: underline;
}

.content-table {
  padding: 40px 10px;
  width: 100%;
  margin: 0;
}

.banner {
  position: relative;
  font-size: 16px;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  font-weight: 300;
  line-height: 1.5;
  overflow-x: auto;
  background-color: #005cbf;
  display: flex;
}

.banner .banner-table {
  padding: 0;
  width: 100%;
  margin: 0 auto;
  align-self: flex-end;
}

.banner h2,
.banner h3,
.banner p,
.banner span {
  color: white;
}

.banner .flex-item {
  max-width: 900px;
  margin: 20px auto;
  padding: 0 30px;
}

.flex-column {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: stretch;
  align-content: stretch;
  box-sizing: border-box;
}

.flex-row-space-between {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  align-content: stretch;
  box-sizing: border-box;
}

.flex-row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: center;
  align-content: stretch;
  box-sizing: border-box;
}

.flex-row-center {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  align-content: stretch;
  box-sizing: border-box;
}

.flex-item-stretch {
  flex: 1 auto;
}

.flex-item-stretch-2 {
  flex: 1 auto;
}

.flex-item-stretch-3 {
  flex: 1 auto;
}

.flex-item-stretch-4 {
  flex: 1 auto;
}

.flex-item-stretch-5 {
  flex: 1 auto;
}

.flex-item {
  margin: 0 20px;
}

.left-align {
  float: left;
}

.right-align {
  float: right;
}

.full-width {
  width: 100%;
}

.badge-text {
  font-size: 30px;
  font-weight: 700;
}

.text {
  margin: 10px 0 10px 0;
  padding: 0;
}

.text-large-margin {
  margin: 15px 0 15px 0;
  padding: 0;
}

.text-small-margin {
  margin: 5px 0 5px 0;
  padding: 0;
}

.text-no-margin {
  margin: 0;
  padding: 0;
}

.image {
  border-radius: 2px;
  width: 100%;
  margin: 15px 0;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  display: flex;
}

.image.center {
  align-self: center;
}

.image img,
.image video {
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  display: table-cell;
  overflow: hidden;
  border-radius: 2px;
}

.adaptive-image {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.image-wrap-text {
  float: left;
  margin: 5px 40px 25px 0;
}

.image-caption {
  width: 100%;
  text-align: center;
  margin-top: -10px;
  margin-bottom: 10px;
}

.max-width-400 {
  max-width: 400px;
}

.max-width-140 {
  max-width: 140px;
}

ol.publication {
  display: flex;
  flex-direction: column-reverse;
  list-style: none;
  margin: 7px 0 7px 0;
  padding: 0;
  flex-wrap: wrap;
}

ol.publication li {
  display: flex;
  align-items: baseline;
  margin: 0;
  padding: 0;
}

ol.publication li p:before {
  line-height: 1;
  margin-right: 5px;
}

ol.publication.C-list {
  counter-reset: C-counter;
}

ol.publication.C-list li p {
  counter-increment: C-counter;
}

ol.publication.C-list li p:before {
  content: "[C"counter(C-counter)"]";
}

ol.publication.J-list {
  counter-reset: J-counter;
}

ol.publication.J-list li p {
  counter-increment: J-counter;
}

ol.publication.J-list li p:before {
  content: "[J"counter(J-counter)"]";
}

ol.publication.T-list {
  counter-reset: T-counter;
}

ol.publication.T-list li p {
  counter-increment: T-counter;
}

ol.publication.T-list li p:before {
  content: "[T"counter(T-counter)"]";
}

ol.publication.O-list {
  counter-reset: O-counter;
}

ol.publication.O-list li p {
  counter-increment: O-counter;
}

ol.publication.O-list li p:before {
  content: "[O"counter(O-counter)"]";
}

ol.publication.P-list {
  counter-reset: P-counter;
}

ol.publication.P-list li p {
  counter-increment: P-counter;
}

ol.publication.P-list li p:before {
  content: "[P"counter(P-counter)"]";
}

ol.publication.M-list {
  counter-reset: M-counter;
}

ol.publication.M-list li p {
  counter-increment: M-counter;
}

ol.publication.M-list li p:before {
  content: "[M"counter(M-counter)"]";
}

ol.publication.F-list {
  counter-reset: F-counter;
}

ol.publication.F-list li p {
  counter-increment: F-counter;
}

ol.publication.F-list li p:before {
  content: "[F"counter(F-counter)"]";
}

ol.publication.A-list {
  counter-reset: A-counter;
}

ol.publication.A-list li p {
  counter-increment: A-counter;
}

ol.publication.A-list li p:before {
  content: "[A"counter(A-counter)"]";
}

ol.nested {
  list-style: none;
  counter-reset: item;
}

ol.nested>li:before {
  counter-increment: item;
  content: counters(item, ".") ". ";
  padding-right: 0.6em;
}

.noselect {
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.center-align-content {
  display: flex;
  justify-content: center;
  align-items: center;
}

.left-align-content {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

.text-large {
  font-size: 20px;
}

.text-small {
  font-size: 12px;
}

.text-italic {
  font-style: italic;
}

.text-justify {
  text-align: justify;
}

.text-center {
  text-align: center;
}

.iframe-container {
  position: absolute;
  top: 61px;
  bottom: 0;
  left: 0;
  height: auto;
  width: 100%;
  min-width: 300px;
}

.iframe {
  border: 0;
  width: 100%;
  height: 100%;
}

.iframe-in-body {
  width: 100%;
  height: 400px;
  border: 1px solid #666666;
  margin: 15px 0;
}

.iframe-in-tab {
  width: 100%;
  height: 400px;
  border: 0;
  margin: 0;
  padding: 0;
}

.force-no-scroll {
  overflow-y: hidden;
}

.force-scroll {
  overflow-y: scroll;
}

.highlight-text {
  font-weight: bold;
}

.custom-text-info,
.custom-text-info p,
.custom-text-info a {
  color: #17a2b8;
}

.custom-text-info a:hover {
  color: #007082;
}

.custom-text-primary,
.custom-text-primary p,
.custom-text-primary a {
  color: #007bff;
}

.custom-text-primary a:hover {
  color: #005cbf;
}

.custom-text-danger,
.custom-text-danger p,
.custom-text-danger a {
  color: #dc3545;
}

.custom-text-danger a:hover {
  color: #a71120;
}

.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: center;
  align-content: stretch;
  box-sizing: border-box;
  width: 100%;
  padding: 0 5px;
}

.gallery>a.flex-column,
.gallery>div.flex-column {
  color: black;
  text-decoration: none;
  padding: 15px;
  cursor: default;
}

.gallery>a.flex-column>img,
.gallery>a.flex-column>video,
.gallery>div.flex-column>img,
.gallery>div.flex-column>video {
  border-radius: 2px;
  width: 100%;
  background-image: url(../img/loading.gif);
  background-repeat: no-repeat;
  background-size: 30px 30px;
  background-position: center;
  min-height: 50px;
}

.gallery>a.flex-column>div,
.gallery>div.flex-column>div,
.gallery>a.flex-column>h3,
.gallery>div.flex-column>h3 {
  width: 100%;
  text-align: center;
}

.masonry {
  column-count: 2;
  column-fill: balance;
  column-gap: 0;
  box-sizing: border-box;
  width: 100%;
  padding: 0 5px;
  position: relative;
}

.masonry figure {
  break-inside: avoid;
  page-break-inside: avoid;
  border: 0;
  color: black;
  text-decoration: none;
  padding: 10px;
  margin: 0;
  cursor: default;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  border: 5px solid transparent;
  position: relative;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: stretch;
  align-content: stretch;
}

.masonry figure.selected {
  border: 5px solid #007bff;
  -moz-box-shadow: inset 0 0 4px 1px #6d6d6d;
  -webkit-box-shadow: inset 0 0 4px 1px #6d6d6d;
  box-shadow: inset 0 0 4px 1px #6d6d6d;
}

.masonry figure>img,
.masonry figure>video {
  width: 100%;
  background-image: url(../img/loading.gif);
  background-repeat: no-repeat;
  background-size: 30px 30px;
  background-position: center;
  min-height: 50px;
  display: block;
  box-sizing: border-box;
  position: relative;
}

.masonry figure>figcaption {
  position: absolute;
  bottom: max(min(2vw, 20px), 15px);
  left: max(min(2vw, 20px), 15px);
  right: max(min(2vw, 20px), 15px);
  font-family: 'Oswald', Helvetica, Arial, sans-serif;
  width: auto;
  display: block;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-size: 25px;
  font-size: max(min(6vw, 21px), 16px);
  line-height: 1.3;
  font-weight: bold;
  color: #fff;
  text-align: center;
  background-color: transparent;
  text-shadow: -1px 1px 0 #000, 1px 1px 0 #000, 1px -1px 0 #000, -1px -1px 0 #000;
}

.masonry figure>figcaption.text-only {
  position: initial;
  background-color: rgb(80, 80, 80);
  padding: 20px 20px;
  text-shadow: none;
}

.masonry figure>figcaption.text-bottom {
  position: initial;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  padding: 5px 5px;
  text-shadow: none;
  color: #000;
  font-weight: normal;
  font-size: 16px;
}

.masonry figure>div {
  width: calc(100% - 20px);
  display: block;
  box-sizing: border-box;
  position: absolute;
  line-height: 2;
  top: 10px;
  left: 10px;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  font-size: 14px;
  background-color: rgba(255, 255, 255, 0.5);
  color: #000;
  text-align: center;
  padding: 0;
  height: 30px;
  margin: 0;
}

.masonry figure>div>a {
  cursor: alias;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  font-size: 14px;
  color: #000;
  text-decoration: underline;
}

.custom-table-container {
  display: grid;
  width: fit-content;
  width: -moz-fit-content;
  margin: 15px 0;
}

.custom-table-container.center {
  margin-left: auto;
  margin-right: auto;
}

.custom-table {
  display: block;
  overflow-x: auto;
  border: 1px solid #666666;
  border-collapse: collapse;
  border-spacing: 0;
  empty-cells: show;
  margin: 0;
  padding: 0;
}

.custom-table thead {
  text-align: left;
  border-bottom: 1px solid #666666;
}

.custom-table tfoot {
  border-top: 1px solid #666666;
}

.custom-table tr.bg-color-gray {
  background-color: #dadada;
}

.custom-table tr.bg-color-light-gray {
  background-color: #efefef;
}

.custom-table td,
.custom-table th {
  padding: 5px 10px;
}

.custom-survey p.custom-answer-survey {
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  box-sizing: border-box;
  padding: 5px 10px;
  margin-top: 15px;
  margin-bottom: 0;
  margin-right: 0;
  margin-left: 0;
  background: rgb(255, 255, 255);
  border: 1px solid #7d7d7d;
  font-size: 18px;
  outline: none;
  border-radius: 0;
  width: 100%;
  white-space: pre-wrap;
  word-wrap: break-word;
  overflow-y: visible;
  overflow-x: hidden;
  min-height: 40px;
  word-break: break-word;
  hyphens: auto;
}

.custom-survey input.custom-textbox-survey,
.custom-survey textarea.custom-textbox-survey {
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  box-sizing: border-box;
  padding: 5px 10px;
  background: rgb(255, 255, 255);
  border: 1px solid #7d7d7d;
  font-size: 18px;
  outline: none;
  border-radius: 0;
  resize: none;
  width: 100%;
  white-space: pre-wrap;
  word-wrap: break-word;
  overflow-y: visible;
  overflow-x: hidden;
  min-height: 130px;
}

.custom-survey input[readonly].custom-textbox-survey,
.custom-survey textarea[readonly].custom-textbox-survey {
  cursor: default;
  background: rgb(230, 230, 230);
}

.custom-survey .custom-radio-group-survey {
  column-count: 1;
  column-fill: balance;
  column-gap: 0;
}

.custom-survey .custom-radio-group-survey.image-only {
  column-count: 2;
  column-fill: balance;
  column-gap: 0;
}

.custom-survey .custom-radio-group-survey div {
  display: flex;
  position: relative;
  width: 100%;
  break-inside: avoid;
}

.custom-survey .custom-radio-group-survey label>img {
  width: calc(100% - 5px);
  margin-top: 5px;
  margin-bottom: 10px;
  border-radius: 51%;
  box-shadow: 0 0px 4px rgba(0, 0, 0, 0.32), 0 0px 10px rgba(0, 0, 0, 0.23);
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label {
  position: relative;
  padding: 10px 10px 10px 48px;
  cursor: pointer;
  font-size: 16px;
  line-height: 1.8;
  display: grid;
  color: black;
  border: 0;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  width: 100%;
}

.custom-survey .custom-radio-group-survey.image-only input[type="radio"]+label,
.custom-survey .custom-radio-group-survey.image-only input[type="checkbox"]+label {
  padding: 10px;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure {
  break-inside: avoid;
  page-break-inside: avoid;
  border: 0;
  color: black;
  text-decoration: none;
  padding: 0;
  margin: 0 auto;
  cursor: pointer;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  position: relative;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: stretch;
  align-content: stretch;
  width: 100%;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure>img,
.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure>video,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure>img,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure>video {
  width: 100%;
  background-image: url(../img/loading.gif);
  background-repeat: no-repeat;
  background-size: 30px 30px;
  background-position: center;
  min-height: 50px;
  display: block;
  box-sizing: border-box;
  position: relative;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure>figcaption,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure>figcaption {
  position: absolute;
  bottom: max(min(2vw, 10px), 5px);
  left: max(min(2vw, 10px), 5px);
  right: max(min(2vw, 10px), 5px);
  font-family: 'Oswald', Helvetica, Arial, sans-serif;
  width: auto;
  display: block;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-size: 25px;
  font-size: max(min(4.5vw, 20px), 16px);
  line-height: 1.3;
  font-weight: bold;
  color: #fff;
  text-align: center;
  background-color: transparent;
  text-shadow: -1px 1px 0 #000, 1px 1px 0 #000, 1px -1px 0 #000, -1px -1px 0 #000;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure>figcaption.text-only,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure>figcaption.text-only {
  position: initial;
  background-color: rgb(80, 80, 80);
  padding: 25px 25px;
  text-shadow: none;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure>div,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure>div {
  width: 100%;
  display: block;
  box-sizing: border-box;
  position: absolute;
  line-height: 2;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  font-size: 14px;
  background-color: rgba(255, 255, 255, 0.5);
  color: #000;
  text-align: center;
  padding: 0;
  height: 30px;
  margin: 0;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label>figure>div>a,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label>figure>div>a {
  cursor: alias;
  font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  font-size: 14px;
  color: #000;
  text-decoration: underline;
}

.custom-survey .custom-radio-group-survey input[type="radio"]:not(:disabled):hover,
.custom-survey .custom-radio-group-survey input[type="checkbox"]:not(:disabled):hover {
  color: #333333;
  background-color: #eeeeee;
}

.custom-survey .custom-radio-group-survey input[type="radio"]:disabled,
.custom-survey .custom-radio-group-survey input[type="checkbox"]:disabled {
  opacity: 0.4;
}

.custom-survey .custom-radio-group-survey input[type="radio"],
.custom-survey .custom-radio-group-survey input[type="checkbox"] {
  padding: 0;
  text-align: center;
  outline: none;
  cursor: pointer;
  box-shadow: none;
  transition: background-color 0.1s, box-shadow 0.1s;
  text-decoration: none;
  box-sizing: border-box;
  background-color: white;
  border: 0;
  border-spacing: 0;
  display: inline-block;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  position: absolute;
  left: -9999px;
}

.custom-survey .custom-radio-group-survey input[type="radio"]:checked+label,
.custom-survey .custom-radio-group-survey input[type="checkbox"]:checked+label {
  color: white;
  background-color: #007bff;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label:before,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label:before {
  content: '';
  position: absolute;
  left: 14px;
  top: 14px;
  width: 20px;
  height: 20px;
  border: 1px solid #aaa;
  background: #fff;
  z-index: 1;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label:before {
  border-radius: 100%;
}

.custom-survey .custom-radio-group-survey input[type="checkbox"]+label:before {
  border-radius: 2px;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label:after,
.custom-survey .custom-radio-group-survey input[type="checkbox"]+label:after {
  content: '';
  width: 14px;
  height: 14px;
  background: #005cbf;
  position: absolute;
  top: 18px;
  left: 18px;
  -webkit-transition: all 0.1s ease;
  transition: all 0.1s ease;
  z-index: 1;
}

.custom-survey .custom-radio-group-survey input[type="radio"]+label:after {
  border-radius: 100%;
}

.custom-survey .custom-radio-group-survey input[type="checkbox"]+label:after {
  border-radius: 2px;
}

.custom-survey .custom-radio-group-survey input[type="radio"]:not(:checked)+label:after,
.custom-survey .custom-radio-group-survey input[type="checkbox"]:not(:checked)+label:after {
  opacity: 0;
  -webkit-transform: scale(0);
  transform: scale(0);
}

.custom-survey .custom-radio-group-survey input[type="radio"]:checked+label:after,
.custom-survey .custom-radio-group-survey input[type="checkbox"]:checked+label:after {
  opacity: 1;
  -webkit-transform: scale(1);
  transform: scale(1);
}

.custom-survey {
  padding: 25px;
  background-color: #e7e7e7;
  border: 1px solid #2f2f2f;
  border-radius: 0;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
}

.custom-survey .text {
  margin-top: 0;
  margin-bottom: 0;
  color: black;
}

.custom-survey h3 {
  margin-top: 0;
}

.custom-survey .custom-textbox-survey {
  color: black;
}

.custom-survey textarea.custom-textbox-survey::-webkit-input-placeholder {
  /* Edge */
  color: #a8a8a8;
}

.custom-survey textarea.custom-textbox-survey:-ms-input-placeholder {
  /* Internet Explorer */
  color: #a8a8a8;
}

.custom-survey textarea.custom-textbox-survey::placeholder {
  color: #a8a8a8;
}

.custom-survey.answer-mode {
  background-color: #afafaf;
  border: 1px solid #5d5d5d;
}

.custom-survey.answer-mode .custom-radio-group-survey input[type="radio"]+label,
.custom-survey.answer-mode .custom-radio-group-survey input[type="checkbox"]+label {
  border: 3px solid #afafaf;
}

.custom-survey.answer-mode .custom-radio-group-survey input[type="radio"]:not(.highlight)+label,
.custom-survey.answer-mode .custom-radio-group-survey input[type="checkbox"]:not(.highlight):checked+label {
  color: black;
  background-color: #afafaf;
}

.custom-survey.answer-mode .custom-radio-group-survey input[type="radio"].highlight+label,
.custom-survey.answer-mode .custom-radio-group-survey input[type="checkbox"].highlight+label {
  box-shadow: 0px 0px 0px 5px white inset;
  background-color: #007bff;
  color: white;
}

.custom-survey.answer-mode .custom-textbox-survey {
  color: #636363;
}

.custom-survey.answer-mode .custom-textbox-survey:disabled {
  background: #dddddd;
}

.no-top-margin {
  margin-top: 0;
}

.no-bottom-margin {
  margin-bottom: 0;
}

.break-long-url {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

  -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;

  /* Adds a hyphen where the word breaks, if supported (No Blink) */
  -ms-hyphens: auto;
  -moz-hyphens: auto;
  -webkit-hyphens: auto;
  hyphens: auto;
}

.graph-title {
  font-size: 20px;
  margin-bottom: 0;
  margin-top: 15px;
}

.add-top-margin {
  margin-top: 15px;
}

.add-top-margin-small {
  margin-top: 5px;
}

.add-top-margin-large {
  margin-top: 30px;
}

.add-bottom-margin {
  margin-bottom: 15px;
}

.add-bottom-margin-small {
  margin-bottom: 5px;
}

.add-bottom-margin-large {
  margin-bottom: 30px;
}

@media screen and (min-width: 900px) {
  .flex-item-stretch {
    flex: 1;
  }

  .flex-item-stretch-2 {
    flex: 2;
  }

  .flex-item-stretch-3 {
    flex: 3;
  }

  .flex-item-stretch-4 {
    flex: 4;
  }

  .flex-item-stretch-5 {
    flex: 5;
  }
}

@media screen and (max-width: 750px) {
  .logo {
    -webkit-tap-highlight-color: transparent;
  }

  .menu .menu-button {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: flex-end;
    align-items: center;
    align-content: stretch;
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
  }

  .menu .menu-button:focus {
    pointer-events: none;
  }

  .menu .menu-button:focus+.menu-items {
    display: block;
  }

  .menu .menu-button:focus+.menu-items>a,
  .menu .menu-button:focus+.menu-items>div {
    display: block;
  }

  .menu .menu-items {
    display: none;
    width: 100%;
    margin-bottom: 10px;
    align-self: baseline;
  }

  .menu .menu-items:hover {
    display: block;
  }

  .menu .menu-items>a:not(:last-child),
  .menu .menu-items>div:not(:last-child) {
    margin-right: 0;
  }

  .menu .menu-items>a,
  .menu .menu-items>div {
    display: block;
    width: 100%;
    padding: 10px 0;
    border-top: 1px solid rgba(255, 255, 255, 0.5);
  }

  .menu .menu-items .dropdown {
    padding-bottom: 0;
  }

  .menu .menu-items .dropdown .dropdown-content {
    margin-top: 10px;
    position: relative;
    display: block;
    background-color: inherit;
    color: inherit;
    box-shadow: none;
    border-top: 0;
  }

  .menu .menu-items .dropdown .dropdown-content a {
    border-top: 1px solid rgba(255, 255, 255, 0.5);
    color: rgba(255, 255, 255, 0.8);
    padding: 10px 20px;
    text-decoration: none;
    display: block;
    text-align: left;
  }

  .menu .menu-items .dropdown .dropdown-content a::before {
    content: "";
    display: inline-block;
    width: 0.5em;
    height: 0.5em;
    margin-right: 0.5em;
    margin-top: 0.25em;
    border-left: 1px solid;
    border-bottom: 1px solid;
    vertical-align: top;
    opacity: 0.5;
  }

  .menu .menu-items .dropdown .dropdown-content a:hover {
    background-color: inherit;
    color: inherit;
  }

  .menu .menu-items .dropdown .dropbtn {
    margin-top: 0;
    display: block;
    width: 100%;
    text-align: left;
  }

  .image-wrap-text {
    max-width: 100%;
    margin-bottom: 20px;
    margin-right: 0;
  }
}

@media screen and (min-width: 900px) {
  .masonry {
    column-count: 3;
  }

  .custom-survey .custom-radio-group-survey.image-only {
    column-count: 2;
  }

  .gallery>a.flex-column,
  .gallery>div.flex-column {
    flex: 1 0 25%;
    max-width: 25%;
  }
}

@media screen and (min-width: 700px) and (max-width: 900px) {
  .masonry {
    column-count: 3;
  }

  .custom-survey .custom-radio-group-survey.image-only {
    column-count: 2;
  }

  .gallery>a.flex-column,
  .gallery>div.flex-column {
    flex: 1 0 33.3%;
    max-width: 33.3%;
  }
}

@media screen and (min-width: 500px) and (max-width: 700px) {
  .masonry {
    column-count: 2;
  }

  .custom-survey .custom-radio-group-survey.image-only {
    column-count: 1;
  }

  .gallery>a.flex-column,
  .gallery>div.flex-column {
    flex: 1 0 50%;
    max-width: 50%;
  }
}

@media screen and (max-width: 500px) {
  .masonry {
    column-count: 1;
  }

  .custom-survey .custom-radio-group-survey.image-only {
    column-count: 1;
  }

  .gallery>a.flex-column,
  .gallery>div.flex-column {
    flex: 1 0 100%;
    max-width: 100%;
  }
}
