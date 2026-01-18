<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>AI Trading Platform</title>

<script src="https://unpkg.com/lightweight-charts@4.1.1/dist/lightweight-charts.standalone.production.js"></script>

<style>
  body {
    margin: 0;
    background: #0b0e11;
    color: white;
    font-family: Arial, sans-serif;
    text-align: center;
  }
  #chart {
    width: 90%;
    height: 400px;
    margin: 20px auto;
  }
  button, input {
    padding: 8px;
    margin: 5px;
  }
</style>
</head>

<body>

<h1>AI Trading Platform</h1>

<input id="symbol" placeholder="AAPL (simulated)" />
<button onclick="loadChart()">Load Chart</button>
<button onclick="runAI()">AI Portfolio</button>
<button onclick="runBacktest()">Backtest</button>

<div id="chart"></div>
<pre id="output"></pre>

<script>
document.addEventListener("DOMContentLoaded", () => {

  const chart = LightweightCharts.createChart(
    document.getElementById("chart"),
    {
      layout: {
        background: { color: "#0b0e11" },
        textColor: "#d1d4dc"
      },
      grid: {
        vertLines: { color: "#1f2933" },
        horzLines: { color: "#1f2933" }
      }
    }
  );

  const series = chart.addLi
