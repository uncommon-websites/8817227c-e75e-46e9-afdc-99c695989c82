<script lang="ts">
  export let text = "Get a quote";
  export let href = "#";
</script>

<div class="bg-black text-white text-[11px] font-medium py-3 px-4 flex justify-between items-center tracking-wide">
  <div class="flex-1 text-center">
    <span class="opacity-90">Fast turnaround times • 2 to 8 weeks from contract to installation • Family-owned since 1983</span>
  </div>
  <a {href} class="bg-[#ff4d28] hover:bg-[#e03a15] text-white px-3 py-1.5 rounded text-[10px] font-bold uppercase tracking-wider ml-4 transition-colors">
    {text}
  </a>
</div>
