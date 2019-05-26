Swop is a decentralized application powered by smart contract that allows users to swap paid reservations/bookings through blockchain.

Several consumers lose money on paid bookings and reservations which they cannot attend to especially if the establishment does not allow cancellation. This application offers the possibility of the person who booked to be able to swap the booking to another person and get the original amount.

Available Functions:
	1) postBooking - This function allows poster who have paid booking to publish their booking details that is available for swapping. They have to enter the Company name, Date, Amount
	2) retrieveBooking - This function will be called by swapper who are searching for available posted booking. For this smart contract, booking will be retrieved first by address and will return the amount
	3) swapBooking - This function will pay the original poster the amount and the 10% admin fee to the contract
	4) addAdminFee - This is  a private function to add a 10% admin fee on top of the original amount of the booking
	5) getAdminFee - This is a private function to get the 10% admin fee of the original amount of booking
    6) refundBooking - This function is used to refund the swopper the amount in case of any dispute. Only the contract owner can execute this function

EtherScan Contract Address: 0x9876e235a87f520c827317a8987c9e1fde804485
EtherScan Link: https://etherscan.io/address/0x9876e235a87f520c827317a8987c9e1fde804485
