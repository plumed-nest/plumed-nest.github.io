**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmkj6or:07341] *** Process received signal ***
[runnervmkj6or:07341] Signal: Aborted (6)
[runnervmkj6or:07341] Signal code:  (-6)
[runnervmkj6or:07341] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe479645330]
[runnervmkj6or:07341] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe47969eb2c]
[runnervmkj6or:07341] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe47964527e]
[runnervmkj6or:07341] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4796288ff]
[runnervmkj6or:07341] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe479aa5ff5]
[runnervmkj6or:07341] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe479abb0da]
[runnervmkj6or:07341] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe479aa5a55]
[runnervmkj6or:07341] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe479aa5a6f]
[runnervmkj6or:07341] [ 8] plumed(+0x146dd)[0x5622382fc6dd]
[runnervmkj6or:07341] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe47962a1ca]
[runnervmkj6or:07341] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe47962a28b]
[runnervmkj6or:07341] [11] plumed(+0x15365)[0x5622382fd365]
[runnervmkj6or:07341] *** End of error message ***
</pre>
{% endraw %}
