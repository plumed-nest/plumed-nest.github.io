**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
(download [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label n4 : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az95-172:33746] *** Process received signal ***
[fv-az95-172:33746] Signal: Aborted (6)
[fv-az95-172:33746] Signal code:  (-6)
[fv-az95-172:33746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f14d346e210]
[fv-az95-172:33746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f14d346e18b]
[fv-az95-172:33746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f14d344d859]
[fv-az95-172:33746] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f14d36d5911]
[fv-az95-172:33746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f14d36e138c]
[fv-az95-172:33746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f14d36e13f7]
[fv-az95-172:33746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f14d36e16a9]
[fv-az95-172:33746] [ 7] plumed(+0xf47d)[0x560783bde47d]
[fv-az95-172:33746] [ 8] plumed(+0x14004)[0x560783be3004]
[fv-az95-172:33746] [ 9] plumed(+0xf698)[0x560783bde698]
[fv-az95-172:33746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f14d344f0b3]
[fv-az95-172:33746] [11] plumed(+0xf76e)[0x560783bde76e]
[fv-az95-172:33746] *** End of error message ***
</pre>
{% endraw %}
