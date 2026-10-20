# Fuzz leak 1

CASE L1 rp opened in a block before a table, never closed.

<rp>
<table>
<tr><td>r1</td><td>ZZL1a</td></tr>
</table>

END L1

ZZL1b after
