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
[pkrvm7jw40e0xgp:12862] *** Process received signal ***
[pkrvm7jw40e0xgp:12862] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12862] Signal code:  (-6)
[pkrvm7jw40e0xgp:12862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99e5445330]
[pkrvm7jw40e0xgp:12862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99e549eb2c]
[pkrvm7jw40e0xgp:12862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99e544527e]
[pkrvm7jw40e0xgp:12862] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99e54288ff]
[pkrvm7jw40e0xgp:12862] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99e58a5ff5]
[pkrvm7jw40e0xgp:12862] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99e58bb0da]
[pkrvm7jw40e0xgp:12862] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99e58a5a55]
[pkrvm7jw40e0xgp:12862] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99e58a5a6f]
[pkrvm7jw40e0xgp:12862] [ 8] plumed(+0x146dd)[0x55b28b4226dd]
[pkrvm7jw40e0xgp:12862] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99e542a1ca]
[pkrvm7jw40e0xgp:12862] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99e542a28b]
[pkrvm7jw40e0xgp:12862] [11] plumed(+0x15365)[0x55b28b423365]
[pkrvm7jw40e0xgp:12862] *** End of error message ***
</pre>
{% endraw %}
