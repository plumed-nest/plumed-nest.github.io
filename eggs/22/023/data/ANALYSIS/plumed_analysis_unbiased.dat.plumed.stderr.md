**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmkj6or:06743] *** Process received signal ***
[runnervmkj6or:06743] Signal: Aborted (6)
[runnervmkj6or:06743] Signal code:  (-6)
[runnervmkj6or:06743] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7fa1645330]
[runnervmkj6or:06743] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7fa169eb2c]
[runnervmkj6or:06743] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7fa164527e]
[runnervmkj6or:06743] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7fa16288ff]
[runnervmkj6or:06743] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7fa1aa5ff5]
[runnervmkj6or:06743] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7fa1abb0da]
[runnervmkj6or:06743] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7fa1aa5a55]
[runnervmkj6or:06743] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7fa1aa5a6f]
[runnervmkj6or:06743] [ 8] plumed(+0x146dd)[0x5607ce4b26dd]
[runnervmkj6or:06743] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7fa162a1ca]
[runnervmkj6or:06743] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7fa162a28b]
[runnervmkj6or:06743] [11] plumed(+0x15365)[0x5607ce4b3365]
[runnervmkj6or:06743] *** End of error message ***
</pre>
{% endraw %}
