## [Unveiling the Impact of User-Agent Reduction and Client Hints: A Measurement Study](https://homes.esat.kuleuven.be/~asenol/ua-reduction/user_agent_reduction_wpes_23.pdf)

To appear at [WPES'23](https://www.wpes2023.conf.kth.se/)

This study examines recent changes in browser behavior related to user-agent string. Browsers including Chrome have reduced the identifying information in user-agent strings to enhance user privacy. However, Chrome has also introduced high-entropy user-agent client hints (UA-CH) and new JavaScript API to provide access to specific browser details. The study assesses the impact of these changes on the top 100,000 websites by using an instrumented crawler to measure access to high-entropy browser features via UA-CH HTTP headers and the JavaScript API. It also investigates whether tracking, advertising, and browser fingerprinting scripts have started using these new client hints and the JavaScript API.

For more detailed overview please check [the project's website](https://homes.esat.kuleuven.be/~asenol/ua-reduction/) or read [the paper](https://homes.esat.kuleuven.be/~asenol/ua-reduction/user_agent_reduction_wpes_23.pdf).
