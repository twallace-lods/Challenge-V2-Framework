<style>
    .instructions h1 {
  padding-top: 1em;
}
.page {
  /* padding: 15px 20px; */
  padding: 1em 1.4em;
}
.page > p:nth-child(3) {
  padding: 0 0 .75em .5em;
}

/* Page 0 */

.instructions #instructionschallenge-name {
  font-weight: normal;
  border-bottom: solid 1px #eee;
  border-top: none;
  font-size: 1.75em;
  padding: 0 1.25em .5em .75em;
  margin: 0 auto;
}

.instructions #instructionschallenge-name > div > p {
  margin: .5em 0 .5em 0;
  color: #666;
}

h1, h2 {
    color: #666;
}

.instructions ol,
.instructions ul {
  padding: 0 1em;
}

#page0 h2 {
  margin-top: 1.5em;
}

.instructions .labhelp ul,
.instructions .labhelp li {
  list-style: none;
  padding: 3px;
  margin-left: 1.25em;
}

#page0 details span[class$="-icon"] {
  margin: 1.1em 0 1.1em 3em;
}

/* Logos */

.instructions div[class*="logo-"] {
  margin: 0 auto;
  max-height: 15em;
  height: 40vw;
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
}

.instructions .logo-guided {
  background-image: url(https://lodmanuals.blob.core.windows.net/lms/2020%20Challenge%20Labs%20Graphics/Challenge-Labs-Guided-16x9v1.1.jpg);
}
.instructions .logo-advanced {
  background-image: url(https://lodmanuals.blob.core.windows.net/lms/2020%20Challenge%20Labs%20Graphics/Challenge-Labs-Advanced-16x9.jpg);
}
.instructions .logo-expert {
  background-image: url(https://lodmanuals.blob.core.windows.net/lms/2020%20Challenge%20Labs%20Graphics/Challenge-Labs-Expert-16x9.jpg);
}

/* Tables */

.page table td {
  padding: 0.4em;
  max-width: 18em;
  overflow-wrap: break-word;
}

.instructions details table {
  margin: 1.5em 0 2em 0;
  background-color: red
}

/* Icons */

.instructions .typeIcon::before {
  border: solid 1px;
  content: "T";
  font-family: "font-family: Consolas,Monaco,Lucida Console,Liberation Mono,DejaVu Sans Mono,Bitstream Vera Sans Mono,Courier New;";
  font-weight: bold;
  color: green;
  vertical-align: middle;
  width: 7px;
  height: 17px;
  padding: .3em .7em .3em .5em;
  margin: auto .75em auto 1em;
}

.instructions .copyIcon::before {
  content: "\e8c8";
  font-family: "labclient";
  font-size: 1.5em;
  margin: auto 1em auto 1em;
  color: green;
}

.instructions .typeIcon,
.instructions .copyIcon {
  display: flex;
  margin: 1.1em 0 1.1em 2.1em;
}

.instructions details {
  margin: .5em 0;
}

.instructions ::marker {
  display: none;
}

.instructions summary {
  list-style: none;
  margin: 0;
}

.instructions details summary::after {
  display: inline-block;
  content: " ";
  background-image: url("https://raw.githubusercontent.com/LODSContent/Challenge-V2-Framework/main/Assets/Icons/arrow.svg");
  /* Height/width needs to match image bg */
  height: 13.5px;
  width: 7.5px;
  margin-left: 1em;
  transition: transform 250ms ease-in-out 25ms;
  transform: rotate(270deg);
  vertical-align: middle;
}

.instructions details[open] summary::after {
  transform: rotate(90deg);
}

.instructions details[class$="-icon"] summary,
.instructions span[class$="-icon"] {
  padding: .4em 1em .4em 3.5em;
  display: block;
  vertical-align: middle;
}

.instructions .hint-icon summary,
.instructions span.hint-icon {
  background-size: 23px !important;
  background: url(https://raw.githubusercontent.com/LODSContent/Challenge-V2-Framework/main/Assets/Icons/hint-icon.png)
    no-repeat left center;
}
.instructions .info-icon summary,
.instructions span.info-icon {
  background-size: 23px !important;
  background: url(https://raw.githubusercontent.com/LODSContent/Challenge-V2-Framework/main/Assets/Icons/info-icon.png)
    no-repeat left center;
}
.instructions .know-icon summary,
.instructions span.know-icon {
  background-size: 23px !important;
  background: url(https://raw.githubusercontent.com/LODSContent/Challenge-V2-Framework/main/Assets/Icons/know-icon.png)
    no-repeat left center;
}
.instructions .warn-icon summary,
.instructions span.warn-icon {
  background-size: 23px !important;
  background: url(https://raw.githubusercontent.com/LODSContent/Challenge-V2-Framework/main/Assets/Icons/warn-icon.png)
    no-repeat left center;
  color: red;
  padding-left: 2.5em;
}

#instructionsNavigation {
  display: flex;
  align-content: center;
  align-items: center;
}

#instructionsNavigation #previous, #instructionsNavigation #next {
  float: unset;
  padding: 0 5%;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  flex-grow: 1;
}

#instructionsNavigation #previous {
  text-align: left;
}

#instructionsNavigation #next {
  text-align: right;
}

#instructionsNavigation #previous::before {
  position: relative;
  top: 3px;
  right: 2px;
  margin: 0;
}

#instructionsNavigation #next::after {
  position: relative;
  top: 3px;
  left: 4px;
  margin: 0;
}

</style>