**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label refcv : No environments have been found! Please specify a PDB file in the REFERENCE or in the REFERENCE_1, REFERENCE_2, etc keywords
[fv-az530-623:06285] *** Process received signal ***
[fv-az530-623:06285] Signal: Aborted (6)
[fv-az530-623:06285] Signal code:  (-6)
[fv-az530-623:06285] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe0a3442520]
[fv-az530-623:06285] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe0a34969fc]
[fv-az530-623:06285] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe0a3442476]
[fv-az530-623:06285] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe0a34287f3]
[fv-az530-623:06285] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe0a38a2b9e]
[fv-az530-623:06285] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe0a38ae20c]
[fv-az530-623:06285] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe0a38ae277]
[fv-az530-623:06285] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe0a38ae52b]
[fv-az530-623:06285] [ 8] plumed(+0x12f48)[0x56162bf12f48]
[fv-az530-623:06285] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe0a3429d90]
[fv-az530-623:06285] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe0a3429e40]
[fv-az530-623:06285] [11] plumed(+0x131e5)[0x56162bf131e5]
[fv-az530-623:06285] *** End of error message ***
</pre>
{% endraw %}
