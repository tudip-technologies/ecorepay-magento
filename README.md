ecorepay-magento
================

As of now, there is no EcorePay payment gateway module available for Magento.

This repository introduces Ecorepay payment gateway module for Magento.

Following are the step to integrate this module with your Magento project:

	1. Download and extract ZIP of the repository or export after taking clone of this public repository.

	2. Copy/Move "app" folder into your Magento project.

	3. Set your merchant's API Key and Auth token on the line no. 127 and 128 of PaymentMethod.php(\app\code\local\Tudip\Ecorepay\Model\PaymentMethod.php)

	4. Goto "Admin panel -> System -> Configuration -> Sales -> Payment Methods -> Ecorepay" and set Enables to "YES"
	
	5. Thats it! Enjoy Ecorepay on Magento.
	
Please provide your feedback.
