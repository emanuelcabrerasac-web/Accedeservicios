:root {
  --paper: #f4f7fb;
  --surface: #fff;
  --ink: #202d3e;
  --muted: #778597;
  --line: #e1e8f0;
  --green: #1555a6;
  --green-dark: #10386d;
  --green-soft: #e8f0fb;
  --lime: #fff;
  --red: #b34c44;
  --red-soft: #fbefed;
  --amber: #9a742b;
  --amber-soft: #f7f1e3;
  --nav-width: 246px;
  --shadow: 0 12px 36px rgba(19, 54, 100, 0.13);
}
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  background: var(--paper);
  color: var(--ink);
  font-family: "DM Sans", sans-serif;
  font-size: 14px;
  -webkit-font-smoothing: antialiased;
}
button,
input,
select {
  font: inherit;
}
button {
  cursor: pointer;
}
.app-shell {
  min-height: 100vh;
}
.workspace {
  margin-right: var(--nav-width);
  padding: 0 46px;
  min-height: 100vh;
  max-width: 1750px;
}
.topbar {
  height: 68px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 1px solid #e2e6df;
}
.breadcrumb {
  display: flex;
  align-items: center;
  gap: 10px;
  color: var(--muted);
  font-size: 12px;
}
.breadcrumb strong {
  color: #34443a;
  font-weight: 600;
}
.breadcrumb-divider {
  color: #b4bbb5;
}
.topbar-right {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 11px;
  color: var(--muted);
}
.live-dot {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #6caa76;
  display: inline-block;
  box-shadow: 0 0 0 3px #e3eee2;
}
.avatar,
.user-avatar {
  border: 0;
  background: #dce7d7;
  color: #35573f;
  border-radius: 50%;
  width: 31px;
  height: 31px;
  display: grid;
  place-items: center;
  font-family: "Manrope", sans-serif;
  font-weight: 800;
  margin-left: 9px;
}
.brand {
  display: flex;
  align-items: center;
  gap: 9px;
  font:
    800 19px "Manrope",
    sans-serif;
  letter-spacing: -0.5px;
}
.brand-mark {
  width: 31px;
  height: 31px;
  border-radius: 9px;
  background: var(--green);
  color: white;
  display: grid;
  place-items: center;
  font:
    800 17px "Manrope",
    sans-serif;
}
.brand-mobile {
  display: none;
}
.side-nav {
  position: fixed;
  top: 0;
  right: 0;
  width: var(--nav-width);
  height: 100vh;
  background: #fff;
  border-left: 1px solid var(--line);
  padding: 27px 17px 18px;
  display: flex;
  flex-direction: column;
  z-index: 5;
}
.side-nav > .brand {
  padding: 0 10px 39px;
}
.nav-caption {
  font-size: 9px;
  font-weight: 700;
  letter-spacing: 1.15px;
  color: #a0a8a2;
  padding: 0 11px 11px;
}
.side-nav nav {
  display: grid;
  gap: 4px;
}
.nav-link {
  border: 0;
  background: transparent;
  color: #66726a;
  width: 100%;
  height: 42px;
  padding: 0 11px;
  display: flex;
  align-items: center;
  gap: 12px;
  text-align: left;
  font-size: 12px;
  border-radius: 5px;
  position: relative;
  transition:
    background 0.18s,
    color 0.18s;
}
.nav-link:hover {
  background: #f5f7f3;
  color: var(--ink);
}
.nav-link.active {
  background: #eaf2ec;
  color: #23533b;
  font-weight: 700;
}
.nav-icon {
  font-size: 18px;
  line-height: 1;
  width: 20px;
  text-align: center;
  color: #77847a;
}
.nav-link.active .nav-icon {
  color: var(--green);
}
.nav-active-mark {
  position: absolute;
  right: 0;
  top: 11px;
  width: 3px;
  height: 20px;
  border-radius: 3px 0 0 3px;
  background: transparent;
}
.nav-link.active .nav-active-mark {
  background: var(--green);
}
.nav-caption-lower {
  margin-top: 31px;
}
.nav-bottom {
  margin-top: auto;
}
.nav-user {
  display: flex;
  align-items: center;
  gap: 10px;
  border-top: 1px solid var(--line);
  padding: 18px 5px 17px;
}
.user-avatar {
  width: 32px;
  height: 32px;
  margin: 0;
  background: #eff2dc;
  color: #657332;
}
.nav-user strong,
.nav-user small {
  display: block;
}
.nav-user strong {
  font-size: 11px;
  font-weight: 700;
}
.nav-user small {
  font-size: 10px;
  color: var(--muted);
  margin-top: 3px;
}
.user-menu {
  margin-left: auto;
  font-size: 18px;
  color: #8b948d;
  letter-spacing: 2px;
}
.nav-version {
  font-size: 8px;
  letter-spacing: 1px;
  color: #a2aaa3;
  padding: 0 5px;
}
.nav-version span {
  padding: 0 4px;
  color: #c1c7c0;
}
.view {
  display: none;
  animation: rise-in 0.3s ease both;
}
.view.active {
  display: block;
}
@keyframes rise-in {
  from {
    opacity: 0;
    transform: translateY(5px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
.page-heading {
  padding: 34px 0 23px;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  gap: 20px;
}
.eyebrow {
  font-size: 9px;
  letter-spacing: 1.2px;
  color: #829087;
  font-weight: 700;
  margin: 0 0 9px;
}
.page-heading h1 {
  font:
    700 30px "Manrope",
    sans-serif;
  letter-spacing: -1px;
  margin: 0;
  color: #23312a;
}
.heading-copy {
  margin: 7px 0 0;
  color: #828b84;
  font-size: 12px;
}
.button {
  height: 39px;
  border-radius: 4px;
  border: 1px solid transparent;
  padding: 0 15px;
  font-size: 11px;
  font-weight: 700;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  white-space: nowrap;
  transition:
    transform 0.15s,
    background 0.15s;
}
.button:hover {
  transform: translateY(-1px);
}
.button-dark {
  background: var(--green);
  color: white;
}
.button-dark:hover {
  background: var(--green-dark);
}
.button-icon {
  font-size: 17px;
  font-weight: 400;
  line-height: 1;
}
.button-outline {
  background: transparent;
  border-color: #d8ded7;
  color: #35483b;
}
.button-outline:hover {
  background: #fff;
}
.hero-banner {
  height: 224px;
  overflow: hidden;
  background: var(--green-dark);
  color: white;
  position: relative;
  padding: 27px 31px 20px;
  border-radius: 5px;
  display: flex;
  align-items: center;
}
.hero-banner:before {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(
      120deg,
      transparent 47%,
      rgba(255, 255, 255, 0.035) 47.3%,
      transparent 47.6%
    ),
    linear-gradient(
      30deg,
      transparent 69%,
      rgba(255, 255, 255, 0.04) 69.2%,
      transparent 69.5%
    );
  background-size:
    47px 47px,
    68px 68px;
  opacity: 0.65;
}
.hero-copy {
  position: relative;
  z-index: 1;
}
.hero-kicker {
  display: flex;
  gap: 8px;
  align-items: center;
  font-size: 8px;
  letter-spacing: 1.4px;
  color: #b6cbbd;
  font-weight: 700;
}
.live-dot.light {
  background: var(--lime);
  box-shadow: 0 0 0 3px rgba(213, 230, 109, 0.12);
  width: 6px;
  height: 6px;
}
.hero-copy h2 {
  font:
    700 25px/1.25 "Manrope",
    sans-serif;
  letter-spacing: -0.6px;
  margin: 15px 0 8px;
}
.hero-copy h2 span {
  color: var(--lime);
}
.hero-copy p {
  margin: 0;
  color: #b8c9bd;
  font-size: 11px;
}
.hero-visual {
  position: absolute;
  right: 7%;
  top: -76px;
  width: 340px;
  height: 340px;
  border: 1px solid rgba(213, 230, 109, 0.17);
  border-radius: 50%;
  display: grid;
  place-items: center;
}
.hero-ring {
  position: absolute;
  border: 1px solid rgba(213, 230, 109, 0.17);
  border-radius: 50%;
}
.ring-one {
  inset: 26px;
}
.ring-two {
  inset: 59px;
  border-style: dashed;
}
.hero-orbit {
  position: absolute;
  width: 14px;
  height: 14px;
  border-radius: 50%;
  background: var(--lime);
  top: 48px;
  right: 68px;
  box-shadow: 0 0 24px rgba(213, 230, 109, 0.45);
}
.hero-bars {
  position: absolute;
  bottom: 113px;
  left: 92px;
  height: 70px;
  display: flex;
  align-items: flex-end;
  gap: 5px;
  transform: rotate(-7deg);
}
.hero-bars i {
  width: 8px;
  border-radius: 2px 2px 0 0;
  background: rgba(213, 230, 109, 0.75);
}
.hero-bars i:nth-child(1) {
  height: 19px;
}
.hero-bars i:nth-child(2) {
  height: 31px;
}
.hero-bars i:nth-child(3) {
  height: 24px;
}
.hero-bars i:nth-child(4) {
  height: 43px;
}
.hero-bars i:nth-child(5) {
  height: 35px;
}
.hero-bars i:nth-child(6) {
  height: 53px;
}
.hero-bars i:nth-child(7) {
  height: 43px;
}
.hero-bars i:nth-child(8) {
  height: 61px;
}
.hero-bars i:nth-child(9) {
  height: 54px;
}
.hero-bars i:nth-child(10) {
  height: 67px;
}
.hero-bars i:nth-child(11) {
  height: 58px;
}
.hero-bars i:nth-child(12) {
  height: 70px;
  background: var(--lime);
}
.hero-visual-label {
  position: absolute;
  top: 179px;
  left: 113px;
  font:
    700 7px/1.4 "Manrope",
    sans-serif;
  letter-spacing: 1px;
  color: #b8c9bd;
}
.hero-foot {
  position: absolute;
  bottom: 17px;
  left: 31px;
  right: 31px;
  display: flex;
  justify-content: space-between;
  border-top: 1px solid rgba(255, 255, 255, 0.15);
  padding-top: 10px;
  color: #a6bdb0;
  font-size: 8px;
  letter-spacing: 1px;
  font-weight: 600;
}
.section-heading {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  margin: 29px 0 14px;
}
.section-heading h2,
.panel-heading h3 {
  font:
    700 16px "Manrope",
    sans-serif;
  letter-spacing: -0.35px;
  margin: 0;
  color: #26352d;
}
.section-heading .eyebrow,
.panel-heading .eyebrow {
  margin-bottom: 5px;
}
.text-button {
  padding: 3px 0;
  border: 0;
  background: transparent;
  color: var(--green);
  font-size: 10px;
  font-weight: 700;
}
.text-button span {
  font-size: 14px;
  margin-left: 4px;
}
.stats-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 12px;
}
.stat-card {
  background: #fff;
  border: 1px solid #e8ebe5;
  min-height: 100px;
  padding: 16px 17px;
  border-radius: 4px;
  position: relative;
  overflow: hidden;
}
.stat-top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: #808b82;
  font-size: 10px;
}
.stat-icon {
  width: 25px;
  height: 25px;
  border-radius: 5px;
  background: #edf4ed;
  color: var(--green);
  display: grid;
  place-items: center;
  font-size: 13px;
}
.stat-value {
  font:
    700 24px "Manrope",
    sans-serif;
  color: #25332b;
  margin-top: 10px;
  letter-spacing: -0.7px;
}
.stat-note {
  font-size: 9px;
  color: #9aa29c;
  margin-top: 2px;
}
.stat-note strong {
  color: #54765e;
  font-weight: 600;
}
.dashboard-bottom {
  display: grid;
  grid-template-columns: minmax(220px, 0.78fr) minmax(0, 1.5fr);
  gap: 13px;
  margin-top: 15px;
}
.panel {
  background: white;
  border: 1px solid #e8ebe5;
  border-radius: 4px;
  padding: 17px;
}
.panel-heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
}
.panel-heading h3 {
  font-size: 13px;
}
.count-badge {
  background: #f3e5e1;
  color: #a45445;
  min-width: 22px;
  height: 22px;
  padding: 0 6px;
  display: grid;
  place-items: center;
  border-radius: 3px;
  font-size: 10px;
  font-weight: 700;
}
.low-stock-list,
.recent-movements {
  margin-top: 13px;
}
.low-stock-item,
.recent-item {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 10px 0;
  border-top: 1px solid #f0f2ee;
}
.low-stock-item:first-child,
.recent-item:first-child {
  border-top: 0;
}
.product-chip {
  width: 30px;
  height: 30px;
  flex: 0 0 30px;
  display: grid;
  place-items: center;
  border-radius: 4px;
  background: #f0f2e9;
  color: #65734b;
  font:
    700 10px "Manrope",
    sans-serif;
}
.low-stock-meta,
.recent-meta {
  min-width: 0;
  flex: 1;
}
.low-stock-meta strong,
.recent-meta strong {
  font-size: 10px;
  font-weight: 600;
  display: block;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow: hidden;
}
.low-stock-meta span,
.recent-meta span {
  display: block;
  margin-top: 3px;
  color: #99a199;
  font-size: 9px;
}
.low-stock-value {
  font:
    700 11px "Manrope",
    sans-serif;
  color: #a45a4b;
}
.movement-symbol {
  width: 25px;
  height: 25px;
  flex: 0 0 25px;
  border-radius: 50%;
  display: grid;
  place-items: center;
  font-size: 12px;
  font-weight: 700;
}
.movement-symbol.in {
  background: var(--green-soft);
  color: var(--green);
}
.movement-symbol.out {
  background: var(--red-soft);
  color: var(--red);
}
.movement-symbol.sale {
  background: #f1edf7;
  color: #7752a1;
}
.recent-amount {
  font:
    600 10px "Manrope",
    sans-serif;
  white-space: nowrap;
}
.workspace-footer {
  padding: 24px 0 19px;
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
  color: #a1aaa2;
  font-size: 8px;
  letter-spacing: 0.8px;
}
.footer-separator {
  padding: 0 5px;
}
.toolbar {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 4px 0 14px;
}
.search-field {
  height: 36px;
  border: 1px solid #e1e6df;
  background: white;
  border-radius: 4px;
  display: flex;
  align-items: center;
  gap: 8px;
  padding: 0 10px;
  color: #94a097;
  min-width: 230px;
}
.search-field > span {
  font-size: 17px;
}
.search-field input {
  border: 0;
  outline: none;
  width: 100%;
  min-width: 0;
  background: transparent;
  font-size: 10px;
  color: var(--ink);
}
.search-field input::placeholder {
  color: #a1aaa3;
}
.toolbar select {
  height: 36px;
  padding: 0 28px 0 10px;
  border: 1px solid #e1e6df;
  background: white;
  border-radius: 4px;
  font-size: 10px;
  color: #59665c;
  outline: 0;
}
.toolbar-count {
  font-size: 9px;
  color: #9aa29c;
  margin-left: auto;
}
.table-panel {
  background: white;
  border: 1px solid #e8ebe5;
  border-radius: 4px;
  overflow: hidden;
}
.table-scroll {
  width: 100%;
  overflow-x: auto;
}
table {
  border-collapse: collapse;
  width: 100%;
  text-align: left;
  white-space: nowrap;
}
thead {
  background: #fafbf9;
}
th {
  height: 38px;
  padding: 0 14px;
  color: #939d94;
  font-size: 8px;
  letter-spacing: 0.75px;
  font-weight: 700;
  border-bottom: 1px solid var(--line);
}
td {
  height: 55px;
  padding: 0 14px;
  border-bottom: 1px solid #eff1ed;
  font-size: 10px;
  color: #59655c;
}
tbody tr:last-child td {
  border-bottom: 0;
}
td strong {
  font-size: 10px;
  font-weight: 600;
  color: #29372e;
}
td small {
  display: block;
  font-size: 9px;
  color: #9aa39c;
  margin-top: 3px;
}
.sku {
  color: #929b93;
  font:
    10px "DM Sans",
    sans-serif;
}
.stock-cell {
  display: flex;
  align-items: center;
  gap: 8px;
}
.stock-track {
  width: 42px;
  height: 4px;
  border-radius: 5px;
  background: #e9eee8;
  overflow: hidden;
}
.stock-fill {
  height: 100%;
  background: #78a77d;
  border-radius: 5px;
}
.stock-fill.low {
  background: #dcaa63;
}
.stock-fill.empty {
  background: #d67d70;
}
.status {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  border-radius: 3px;
  padding: 5px 7px;
  font-size: 9px;
  font-weight: 600;
}
.status:before {
  content: "";
  width: 5px;
  height: 5px;
  border-radius: 50%;
  background: currentColor;
}
.status.ok {
  background: #edf5ee;
  color: #4f8059;
}
.status.low {
  background: #faf2e4;
  color: #9a742b;
}
.status.out {
  background: #fbefed;
  color: #b34c44;
}
.row-menu {
  border: 0;
  background: transparent;
  color: #9da69e;
  font-size: 17px;
  padding: 5px 8px;
}
.empty-state {
  padding: 35px 20px;
  text-align: center;
  color: #929b94;
  font-size: 11px;
}
.hidden {
  display: none !important;
}
.compact-stats {
  margin: 2px 0 15px;
  grid-template-columns: repeat(3, minmax(0, 1fr));
}
.compact-stats .stat-card {
  min-height: 88px;
}
.compact-stats .stat-value {
  font-size: 21px;
  margin-top: 8px;
}
.sales-table-panel .panel-heading {
  padding: 15px 14px;
}
.sales-table-panel .table-scroll {
  border-top: 1px solid #eff1ed;
}
.compact-search {
  min-width: 185px;
  width: 210px;
  height: 31px;
}
.history-summary {
  display: flex;
  gap: 23px;
  align-items: center;
  margin: 1px 0 15px;
  padding: 14px 17px;
  background: #eaf1eb;
  border: 1px solid #dfe9df;
  border-radius: 4px;
}
.history-metric {
  display: flex;
  align-items: baseline;
  gap: 7px;
}
.history-metric strong {
  font:
    700 17px "Manrope",
    sans-serif;
  color: #315a3d;
}
.history-metric span {
  font-size: 9px;
  color: #738476;
}
.history-summary .history-divider {
  height: 24px;
  width: 1px;
  background: #d3e0d5;
}
.report-range {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 19px 21px;
  background: #eaf1eb;
  border: 1px solid #dfe9df;
  border-radius: 4px;
  margin-bottom: 13px;
}
.report-range h2 {
  font:
    700 17px "Manrope",
    sans-serif;
  margin: 0 0 5px;
  color: #294233;
}
.report-range p:last-child {
  font-size: 10px;
  color: #77877b;
  margin: 0;
}
.report-range .eyebrow {
  margin-bottom: 5px;
}
.report-mark {
  font:
    800 33px "Manrope",
    sans-serif;
  color: var(--green);
  letter-spacing: -2px;
}
.report-mark span {
  color: #a7bf55;
}
.report-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 13px;
  margin-top: 14px;
}
.report-products {
  margin-top: 9px;
}
.report-product {
  display: grid;
  grid-template-columns: 26px 1fr auto;
  align-items: center;
  gap: 10px;
  padding: 10px 0;
  border-top: 1px solid #eff1ed;
}
.report-product:first-child {
  border-top: 0;
}
.report-rank {
  font:
    700 10px "Manrope",
    sans-serif;
  color: #a3aca4;
}
.report-product strong {
  font-size: 10px;
  font-weight: 600;
}
.report-product small {
  display: block;
  color: #9aa39c;
  font-size: 9px;
  margin-top: 3px;
}
.report-product-value {
  font:
    600 10px "Manrope",
    sans-serif;
}
.report-note {
  font-size: 9px;
  color: #a0a8a0;
  margin: 13px 0;
}
.modal-backdrop {
  position: fixed;
  inset: 0;
  background: rgba(22, 35, 27, 0.42);
  z-index: 10;
  display: grid;
  place-items: center;
  padding: 18px;
  animation: fade-in 0.15s ease;
}
.modal {
  background: #fff;
  width: min(100%, 450px);
  border-radius: 5px;
  box-shadow: var(--shadow);
  animation: rise-in 0.2s ease;
}
.modal-head {
  padding: 20px 22px 15px;
  border-bottom: 1px solid var(--line);
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}
.modal-head h2 {
  font:
    700 19px "Manrope",
    sans-serif;
  margin: 0;
  letter-spacing: -0.4px;
}
.modal-head p {
  font-size: 10px;
  color: #89938b;
  margin: 5px 0 0;
}
.modal-close {
  border: 0;
  background: transparent;
  color: #818b83;
  font-size: 20px;
  padding: 0 3px;
}
.modal-form {
  padding: 17px 22px 20px;
}
.form-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}
.form-field {
  display: grid;
  gap: 6px;
}
.form-field.full {
  grid-column: 1/-1;
}
.form-field label {
  font-size: 10px;
  font-weight: 600;
  color: #58665c;
}
.form-field input,
.form-field select {
  height: 37px;
  border: 1px solid #dfe5df;
  border-radius: 3px;
  padding: 0 10px;
  outline: 0;
  color: #344139;
  background: white;
  font-size: 11px;
}
.form-field input:focus,
.form-field select:focus {
  border-color: #6e9a79;
  box-shadow: 0 0 0 2px #e9f2eb;
}
.form-field input::placeholder {
  color: #adb5ae;
}
.form-hint {
  font-size: 9px;
  color: #929b94;
  line-height: 1.5;
  margin: 0;
}
.modal-actions {
  display: flex;
  justify-content: flex-end;
  gap: 8px;
  margin-top: 20px;
}
.button-muted {
  height: 36px;
  padding: 0 13px;
  background: white;
  border: 1px solid #e0e5df;
  color: #657068;
  border-radius: 4px;
  font-size: 10px;
  font-weight: 600;
}
.button-submit {
  height: 36px;
  padding: 0 15px;
  background: var(--green);
  border: 0;
  color: white;
  border-radius: 4px;
  font-size: 10px;
  font-weight: 700;
}
.toast {
  position: fixed;
  bottom: 22px;
  left: 50%;
  transform: translate(-50%, 12px);
  background: #253d30;
  color: white;
  padding: 11px 16px;
  border-radius: 4px;
  font-size: 11px;
  box-shadow: var(--shadow);
  opacity: 0;
  pointer-events: none;
  transition:
    opacity 0.18s,
    transform 0.18s;
  z-index: 20;
}
.toast.visible {
  opacity: 1;
  transform: translate(-50%, 0);
}
@keyframes fade-in {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@media (max-width: 1100px) {
  :root {
    --nav-width: 215px;
  }
  .workspace {
    padding: 0 29px;
  }
  .dashboard-bottom {
    grid-template-columns: 1fr 1.3fr;
  }
  .hero-visual {
    right: 0;
  }
  .stats-grid {
    gap: 9px;
  }
  .stat-card {
    padding: 14px;
  }
  .stat-value {
    font-size: 21px;
  }
}
@media (max-width: 780px) {
  :root {
    --nav-width: 0px;
  }
  .side-nav {
    top: auto;
    right: 0;
    bottom: 0;
    width: 100%;
    height: 62px;
    padding: 5px 8px calc(5px + env(safe-area-inset-bottom));
    border-left: 0;
    border-top: 1px solid var(--line);
    display: flex;
    flex-direction: row;
    align-items: center;
  }
  .side-nav > .brand,
  .nav-caption,
  .nav-bottom {
    display: none;
  }
  .side-nav nav {
    display: contents;
  }
  .nav-link {
    height: 50px;
    min-width: 0;
    flex: 1;
    justify-content: center;
    gap: 3px;
    padding: 3px 1px;
    flex-direction: column;
    font-size: 8px;
    border-radius: 4px;
  }
  .nav-icon {
    font-size: 16px;
    height: 17px;
  }
  .nav-active-mark {
    top: auto;
    bottom: 0;
    left: calc(50% - 11px);
    width: 22px;
    height: 2px;
    border-radius: 2px 2px 0 0;
  }
  .workspace {
    margin: 0;
    padding: 0 23px 75px;
  }
  .topbar {
    height: 56px;
  }
  .brand-mobile {
    display: flex;
    font-size: 15px;
  }
  .brand-mobile .brand-mark {
    width: 25px;
    height: 25px;
    font-size: 14px;
  }
  .breadcrumb {
    margin-right: auto;
    margin-left: 14px;
  }
  .topbar-right > span:not(.live-dot) {
    display: none;
  }
  .topbar-right .avatar {
    width: 27px;
    height: 27px;
  }
  .page-heading {
    padding: 27px 0 19px;
  }
  .page-heading h1 {
    font-size: 25px;
  }
  .hero-banner {
    height: 202px;
    padding-left: 23px;
  }
  .hero-copy h2 {
    font-size: 22px;
  }
  .hero-visual {
    right: -120px;
    opacity: 0.75;
  }
  .hero-foot {
    left: 23px;
    right: 23px;
  }
  .dashboard-bottom {
    grid-template-columns: 1fr;
  }
  .stats-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
  .stat-card {
    min-height: 93px;
  }
  .report-grid {
    grid-template-columns: 1fr;
  }
  .workspace-footer {
    padding-bottom: 4px;
  }
  .workspace-footer span:last-child {
    display: none;
  }
  .toolbar {
    flex-wrap: wrap;
  }
  .toolbar-count {
    margin-left: 0;
  }
  .report-range {
    padding: 15px;
  }
  .table-panel {
    margin-bottom: 5px;
  }
}
@media (max-width: 480px) {
  .workspace {
    padding-left: 15px;
    padding-right: 15px;
  }
  .page-heading {
    align-items: flex-start;
    flex-direction: column;
    gap: 14px;
  }
  .page-heading > .button {
    align-self: flex-start;
  }
  .page-heading h1 {
    font-size: 23px;
  }
  .heading-copy {
    font-size: 11px;
  }
  .topbar-right {
    gap: 2px;
  }
  .breadcrumb {
    font-size: 10px;
    gap: 7px;
  }
  .hero-banner {
    height: 190px;
    padding-left: 18px;
  }
  .hero-copy h2 {
    font-size: 19px;
  }
  .hero-copy p {
    font-size: 10px;
  }
  .hero-visual {
    right: -180px;
    opacity: 0.5;
  }
  .hero-foot {
    left: 18px;
    right: 18px;
  }
  .section-heading {
    margin-top: 23px;
  }
  .section-heading h2 {
    font-size: 14px;
  }
  .stats-grid {
    gap: 7px;
  }
  .stat-card {
    padding: 12px 11px;
    min-height: 86px;
  }
  .stat-top {
    font-size: 9px;
  }
  .stat-value {
    font-size: 20px;
  }
  .stat-note {
    font-size: 8px;
  }
  .toolbar {
    gap: 7px;
  }
  .toolbar .search-field {
    width: 100%;
    min-width: 100%;
  }
  .toolbar select {
    flex: 1;
  }
  .toolbar-count {
    font-size: 9px;
  }
  .panel {
    padding: 14px;
  }
  .history-summary {
    gap: 11px;
    justify-content: space-between;
    padding: 12px;
  }
  .history-metric {
    display: block;
  }
  .history-metric strong {
    display: block;
    font-size: 15px;
  }
  .history-metric span {
    font-size: 8px;
  }
  .history-summary .history-divider {
    height: 27px;
  }
  .report-range h2 {
    font-size: 15px;
  }
  .report-mark {
    font-size: 27px;
  }
  .form-grid {
    grid-template-columns: 1fr;
  }
  .form-field.full {
    grid-column: auto;
  }
  .modal-form {
    padding: 15px;
  }
  .modal-head {
    padding: 17px 17px 13px;
  }
  .nav-link {
    font-size: 7px;
  }
}
@media print {
  body {
    background: #fff !important;
    color: #202a24 !important;
  }
  .app-shell,
  .modal-backdrop,
  .toast {
    display: none !important;
  }
  body.printing #report-paper {
    display: block !important;
  }
  #report-paper {
    font-family: "DM Sans", Arial, sans-serif;
    color: #243229;
    padding: 25px;
  }
  #report-paper h1 {
    font:
      700 26px "Manrope",
      Arial,
      sans-serif;
    margin: 0 0 4px;
  }
  #report-paper h2 {
    font:
      700 15px "Manrope",
      Arial,
      sans-serif;
    border-bottom: 1px solid #dfe5df;
    padding-bottom: 8px;
    margin: 22px 0 8px;
  }
  #report-paper .print-subtitle {
    font-size: 11px;
    color: #768078;
    margin: 0 0 25px;
  }
  #report-paper .print-kpis {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
  }
  #report-paper .print-kpi {
    border: 1px solid #dfe5df;
    padding: 13px;
    border-radius: 3px;
  }
  #report-paper .print-kpi span {
    display: block;
    color: #768078;
    font-size: 9px;
  }
  #report-paper .print-kpi strong {
    display: block;
    font:
      700 18px "Manrope",
      Arial,
      sans-serif;
    margin-top: 7px;
  }
  #report-paper table {
    width: 100%;
    border-collapse: collapse;
  }
  #report-paper th,
  #report-paper td {
    height: auto;
    padding: 8px 6px;
    border-bottom: 1px solid #e5e9e4;
    text-align: left;
    font-size: 9px;
  }
  #report-paper th {
    font-size: 8px;
    color: #758078;
  }
  #report-paper .print-footer {
    margin-top: 30px;
    font-size: 8px;
    color: #8b948c;
  }
  @page {
    size: A4;
    margin: 15mm;
  }
}
#report-paper {
  display: none;
}
.report-controls {
  display: grid;
  grid-template-columns: 1.2fr 1fr 1fr auto;
  gap: 12px;
  align-items: end;
  padding: 16px;
  margin: 14px 0;
}
.report-controls-group {
  display: grid;
  gap: 6px;
}
.report-controls label {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.8px;
  color: #6e7d8b;
  text-transform: uppercase;
}
.report-controls input,
.report-controls select {
  width: 100%;
  height: 40px;
  padding: 0 12px;
  border: 1px solid var(--line);
  border-radius: 8px;
  background: #fff;
  color: var(--ink);
}
.chart-panel {
  margin: 16px 0;
}
.chart-wrap {
  width: 100%;
  overflow-x: auto;
}
.chart-legend {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  color: #6e7d8b;
  font-size: 11px;
}
.chart-legend span {
  display: flex;
  align-items: center;
  gap: 7px;
}
.legend-dot {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  display: inline-block;
}
.legend-dot.revenue {
  background: #1555a6;
}
.legend-dot.expense {
  background: #d36a5d;
}
.legend-dot.profit {
  background: #2a9d7d;
}
#financial-chart {
  width: 100%;
  min-width: 640px;
  height: 260px;
  display: block;
}
.chart-grid line {
  stroke: #e6edf4;
  stroke-width: 1;
}
.chart-grid text {
  fill: #8a9aa8;
  font-size: 10px;
}
#financial-chart path:nth-child(1) {
  filter: drop-shadow(0 3px 6px rgba(21, 85, 166, 0.18));
}
.currency-tag {
  background: var(--green-soft);
  color: var(--green);
  padding: 6px 10px;
  border-radius: 999px;
  font:
    700 11px "Manrope",
    sans-serif;
}
.side-nav > .brand,
.brand-mobile {
  background: var(--green);
  color: #fff;
  border-radius: 5px;
}
.side-nav > .brand {
  padding: 8px 10px;
  margin: 0 0 30px;
}
.brand-mobile {
  padding: 3px 9px 3px 3px;
}
.brand-mark {
  background: rgba(255, 255, 255, 0.16);
  color: #fff;
}
.heading-actions {
  display: flex;
  align-items: center;
  gap: 8px;
}
.invoice-table-panel {
  margin-top: 14px;
}
.invoice-table-panel > .panel-heading {
  padding: 15px 14px;
  border-bottom: 1px solid var(--line);
}
.invoice-print-button {
  height: 29px;
  padding: 0 9px;
  font-size: 9px;
}
.invoice-legal-note {
  margin: 11px 0 0;
  color: #8995a2;
  font-size: 9px;
}
.invoice-modal {
  width: min(100%, 680px);
  max-height: calc(100vh - 32px);
  display: flex;
  flex-direction: column;
}
.invoice-modal .modal-form {
  overflow-y: auto;
}
.invoice-section-label {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  margin-bottom: 8px;
}
.invoice-section-label label {
  font-size: 10px;
  font-weight: 600;
  color: #58665c;
}
.invoice-section-label span {
  font-size: 9px;
  color: #8995a2;
}
.invoice-line {
  border: 1px solid var(--line);
  padding: 10px;
  border-radius: 4px;
  margin-bottom: 8px;
  background: #fbfcfe;
}
.invoice-line-heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 8px;
}
.invoice-line-heading strong {
  font-size: 9px;
  color: #657387;
  letter-spacing: 0.5px;
  text-transform: uppercase;
}
.invoice-line-fields {
  display: grid;
  grid-template-columns: minmax(0, 2fr) minmax(75px, 0.65fr) minmax(110px, 1fr);
  gap: 8px;
}
.invoice-line-fields .form-field {
  min-width: 0;
}
.invoice-line-fields input,
.invoice-line-fields select {
  width: 100%;
  min-width: 0;
}
.invoice-remove-line {
  border: 0;
  background: transparent;
  color: #8995a2;
  font-size: 17px;
  line-height: 1;
  padding: 1px 5px;
}
.invoice-add-line {
  border: 0;
  background: transparent;
  color: var(--green);
  font-size: 10px;
  font-weight: 700;
  padding: 4px 0;
}
.invoice-totals {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 8px;
  background: #f2f6fc;
  padding: 11px;
  border-radius: 4px;
}
.invoice-totals > div {
  display: grid;
  gap: 5px;
}
.invoice-totals span {
  font-size: 9px;
  color: #7c8998;
}
.invoice-totals strong {
  font:
    700 13px "Manrope",
    sans-serif;
  color: #2a394b;
}
.invoice-totals .invoice-grand-total {
  text-align: right;
}
.invoice-totals .invoice-grand-total strong {
  font-size: 17px;
  color: var(--green);
}
.invoice-success-modal {
  width: min(100%, 450px);
  padding-bottom: 18px;
}
.invoice-success-body {
  padding: 16px 22px 0;
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 15px;
}
.invoice-success-body > div {
  display: grid;
  gap: 5px;
}
.invoice-success-body span {
  font-size: 8px;
  color: #8290a0;
  letter-spacing: 0.8px;
  font-weight: 700;
}
.invoice-success-body strong {
  font-size: 11px;
  color: #2b3b4d;
}
.invoice-success-body .invoice-success-total {
  grid-column: 1/-1;
  border-top: 1px solid var(--line);
  padding-top: 12px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.invoice-success-body .invoice-success-total strong {
  font:
    700 20px "Manrope",
    sans-serif;
  color: var(--green);
}
.invoice-success-body > p {
  grid-column: 1/-1;
  color: #8995a2;
  font-size: 9px;
  margin: 0;
}
.invoice-success-modal > .modal-actions {
  padding: 0 22px;
}
#invoice-paper {
  display: none;
}
@media (max-width: 600px) {
  .heading-actions {
    width: 100%;
    flex-wrap: wrap;
  }
  .invoice-line-fields {
    grid-template-columns: minmax(0, 1fr) 74px;
  }
  .invoice-line-fields .form-field:last-child {
    grid-column: 1/-1;
  }
  .invoice-success-body {
    padding-left: 16px;
    padding-right: 16px;
  }
  .invoice-success-modal > .modal-actions {
    padding-left: 16px;
    padding-right: 16px;
  }
}
@media print {
  body.printing-invoice #invoice-paper {
    display: block !important;
  }
  #invoice-paper {
    font-family: "DM Sans", Arial, sans-serif;
    color: #253348;
    padding: 20px;
  }
  #invoice-paper .invoice-paper-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    border-bottom: 3px solid #1555a6;
    padding-bottom: 17px;
  }
  #invoice-paper .invoice-paper-brand {
    display: inline-block;
    background: #1555a6;
    color: white;
    padding: 7px 10px;
    border-radius: 3px;
    font:
      800 15px "Manrope",
      Arial,
      sans-serif;
    letter-spacing: 0.4px;
  }
  #invoice-paper h1 {
    font:
      700 23px "Manrope",
      Arial,
      sans-serif;
    margin: 14px 0 3px;
  }
  #invoice-paper .invoice-paper-header p,
  #invoice-paper .invoice-paper-date span {
    font-size: 10px;
    color: #718095;
    margin: 0;
  }
  #invoice-paper .invoice-paper-date {
    display: grid;
    gap: 5px;
    text-align: right;
    font-size: 10px;
  }
  #invoice-paper .invoice-party-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
    padding: 20px 0;
  }
  #invoice-paper .invoice-party-grid section {
    display: grid;
    gap: 5px;
  }
  #invoice-paper .invoice-party-grid section > span {
    font-size: 8px;
    letter-spacing: 1px;
    color: #718095;
    font-weight: 700;
  }
  #invoice-paper .invoice-party-grid strong {
    font-size: 12px;
  }
  #invoice-paper .invoice-party-grid p {
    font-size: 9px;
    margin: 0;
    color: #59697d;
  }
  #invoice-paper table {
    width: 100%;
    border-collapse: collapse;
  }
  #invoice-paper th,
  #invoice-paper td {
    height: auto;
    padding: 9px 6px;
    border-bottom: 1px solid #e1e8f0;
    text-align: left;
    font-size: 9px;
  }
  #invoice-paper th {
    font-size: 8px;
    color: #718095;
  }
  #invoice-paper .invoice-paper-bottom {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    padding-top: 18px;
  }
  #invoice-paper .invoice-paper-bottom > div:first-child {
    display: grid;
    align-content: start;
    gap: 6px;
    font-size: 9px;
  }
  #invoice-paper .invoice-paper-bottom > div:first-child span {
    color: #718095;
  }
  #invoice-paper .invoice-paper-totals {
    width: 235px;
    display: grid;
    gap: 7px;
  }
  #invoice-paper .invoice-paper-totals > div {
    display: flex;
    justify-content: space-between;
    font-size: 10px;
  }
  #invoice-paper .invoice-paper-grand {
    border-top: 2px solid #1555a6;
    padding-top: 9px;
    font-size: 13px !important;
    font-weight: 700;
  }
  #invoice-paper .invoice-paper-legal {
    margin-top: 34px;
    padding-top: 10px;
    border-top: 1px solid #e1e8f0;
    color: #8995a2;
    font-size: 8px;
  }
}
