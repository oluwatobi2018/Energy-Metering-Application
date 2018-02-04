# Energy-Meter-App-
Energy meter app reading volatge, current, instantaneous power, energy used and cost. The data are measured from the circuit and send by arduino via bluetooth over RFCOMM.

Few things that has been done here.
1. Recieve MAC address of all paired devices in List View
2. Connect to HC-05 module of Arduino
3. Parse the data send by arduino format( #220V10C400P4E30Cu~) where #represents start of data and ~ represents end of data and V, C, P, E and Cu for parsing
4. Set Text to parsed data to respective text view
