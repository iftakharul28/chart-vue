<script>
import VueApexCharts from "vue3-apexcharts";
export default {
  components: {
    apexcharts: VueApexCharts,
  },
  data() {
    return {
      chartOptions: {
        chart: {
          type: "area",
          height: 350,
        },
        dataLabels: {
          enabled: false,
        },
        stroke: {
          curve: "straight",
        },
        title: {
          text: "Balances",
          align: "center",
          style: {
            fontSize: "14px",
          },
        },
        fill: {
          opacity: 0.5,
        },
        grid: {
          yaxis: {
            lines: {
              offsetX: -30,
            },
          },
          padding: {
            left: 20,
          },
        },
      },
      series: [
        {
          name: "series1",
          data: [31, 40, 28, 51, 42, 109, 100],
        },
        {
          name: "series2",
          data: [11, 32, 45, 32, 34, 52, 41],
        },
        {
          name: "series3",
          data: [14, 36, 45, 32, 34, 5, 14],
        },
      ],
    };
  },
};
</script>

<template>
  <apexcharts
    width="550"
    type="area"
    :options="chartOptions"
    :series="series"
    class="home__left-chart"
  />
</template>
