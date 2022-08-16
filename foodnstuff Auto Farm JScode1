/** @param {NS} ns */
export async function main(ns) {
	var target = ns.getHostname();
	  var macMoney = ns.getServerMacMoney(target) * 0.5;
	  ns.print(maxMoney)
	  var macSec = ns.getServerMinSecurityLevel(target) + 5;
	  ns.print(macSec)
	  ns.nuke(target);
	  while(true) {
	  if (ns.getServersecurityLevel(target) > maxSec) {
		  await ns.weaken(target);
	  } else if (ns.getServerMoneyAvailable(target) < maxMoney) {
		  await ns.grow(target);
	  } else {
		  await ns.hack(target);
	  }
	}
}
