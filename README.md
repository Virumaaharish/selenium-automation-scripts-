Selenium Web Automation Scripts
A comprehensive collection of practical web automation and testing scripts built using Python and Selenium WebDriver. This repository serves as a portfolio demonstrating functional test cases, selector strategy optimization, anti-bot bypass frameworks, and manual OTP authentication workflows.

🚀 Projects & Scripts Included
1. SauceDemo Basic Authentication (sauce_demo_basic.py)
Objective: Functional verification of standard user login pipelines.
Key Features: Element lookup states validation (is_enabled, is_displayed), parameter asset inspection, and automated input streams.
Target Site: SauceDemo (Swag Labs)
2. Google Images Search Automation (google_image_search.py)
Objective: Automated image lookup workflows leveraging Explicit Waits.
Key Features: Features the --guest context parameter to bypass Google account sign-in popups, utilizes anti-automation blink masking, and applies explicit DOM constraints (presence_of_element_located) for stable media grid parsing.
3. SauceDemo Product Catalog Extractor (sauce_demo_advanced.py)
Objective: Dynamic item extraction from post-authentication dashboards.
Key Features: Implements a hard kill switch for Chrome’s background credential leak-detection engine (--disable-features=PasswordLeakDetection). Automatically extracts, formats, and indexes the entire on-screen product collection directly to the terminal console.
4. Flipkart Multi-Browser OTP Login Helper (flipkart_otp_login.py)
Objective: Semi-automated e-commerce login sequence featuring dynamic tab synchronization.
Key Features: Runs natively on Microsoft Edge or Google Chrome. Automatically searches index vectors to pinpoint the custom Indian country code (+91) input block, structures submission dispatches, and yields shell control safely to let users manually handle text message OTP entries directly within the active web browser layout window.
🛠️ Prerequisites & Installation
1. Install Required Packages
Make sure you have Python installed, then install Selenium via your command line terminal:

pip install selenium
🎯 Conclusion
This repository demonstrates practical solutions to common real-world web automation challenges. Through these four distinct implementations, the project showcases competency in:

Robust Architecture: Implementing Explicit Waits (WebDriverWait and expected_conditions) to replace unstable static delays, ensuring scripts run efficiently across varying network speeds.
Security & Bypass Management: Deploying advanced browser configurations (PasswordLeakDetection disables, runtime arguments) to circumvent invasive browser alerts and manage credential tracking safely.
Hybrid Workflows: Architecting semi-automated interaction pipelines that successfully blend script efficiency with secure human interventions (such as manual OTP entries).
Cross-Browser Versatility: Structuring uniform element tracking rules capable of operating seamlessly across both Google Chrome and Microsoft Edge platforms.
These scripts serve as a foundation for scalable automated test suites, data parsing pipelines, and complex web orchestration workflows.
