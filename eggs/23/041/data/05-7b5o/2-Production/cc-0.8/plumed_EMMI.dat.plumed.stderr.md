**Project ID:** [plumID:23.041]({{ '/' | absolute_url }}eggs/23/041/)  
Stderr for source:  05-7b5o/2-Production/cc-0.8/plumed_EMMI.dat   
Download: [zipped raw stdout](plumed_EMMI.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_EMMI.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: EMMIVOX LABEL=emmi TEMP=300.0 NL_STRIDE=50 NL_DIST_CUTOFF=1.0 NL_GAUSS_CUTOFF=3.0 ATOMS=system-map DATA_FILE=emd_plumed_aligned.dat NORM_DENSITY=2660.966064 RESOLUTION=0.25 SIGMA_MIN=0.2 GPU STATUS_FILE=EMMIStatus WRITE_STRIDE=5000 DBFACT=0.05 MCBFACT_STRIDE=500 BFACT_SIGMA=0.1 SCALE=1.450000 CORRELATION
Maybe a missing space or a typo?
[fv-az1487-606:67810] *** Process received signal ***
[fv-az1487-606:67810] Signal: Aborted (6)
[fv-az1487-606:67810] Signal code:  (-6)
[fv-az1487-606:67810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc4ad442520]
[fv-az1487-606:67810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc4ad4969fc]
[fv-az1487-606:67810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc4ad442476]
[fv-az1487-606:67810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc4ad4287f3]
[fv-az1487-606:67810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fc4ad8a4f26]
[fv-az1487-606:67810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fc4ad8b6d9c]
[fv-az1487-606:67810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fc4ad8b6e07]
[fv-az1487-606:67810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc4ad8b70bb]
[fv-az1487-606:67810] [ 8] plumed(+0x12f48)[0x558dc20abf48]
[fv-az1487-606:67810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc4ad429d90]
[fv-az1487-606:67810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc4ad429e40]
[fv-az1487-606:67810] [11] plumed(+0x131e5)[0x558dc20ac1e5]
[fv-az1487-606:67810] *** End of error message ***
</pre>
{% endraw %}
