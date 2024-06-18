**Project ID:** [plumID:23.041]({{ '/' | absolute_url }}eggs/23/041/)  
Stderr for source:  05-7b5o/2-Production/cc-1.0/plumed_EMMI.dat   
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
[fv-az1272-851:04459] *** Process received signal ***
[fv-az1272-851:04459] Signal: Aborted (6)
[fv-az1272-851:04459] Signal code:  (-6)
[fv-az1272-851:04459] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7e4a842520]
[fv-az1272-851:04459] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7e4a8969fc]
[fv-az1272-851:04459] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7e4a842476]
[fv-az1272-851:04459] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7e4a8287f3]
[fv-az1272-851:04459] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7e4aca2b9e]
[fv-az1272-851:04459] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7e4acae20c]
[fv-az1272-851:04459] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7e4acae277]
[fv-az1272-851:04459] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7e4acae52b]
[fv-az1272-851:04459] [ 8] plumed(+0x12f48)[0x556e9b960f48]
[fv-az1272-851:04459] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7e4a829d90]
[fv-az1272-851:04459] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7e4a829e40]
[fv-az1272-851:04459] [11] plumed(+0x131e5)[0x556e9b9611e5]
[fv-az1272-851:04459] *** End of error message ***
</pre>
{% endraw %}
