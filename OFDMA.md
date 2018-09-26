What is OFDM ?

### Answer:-

➨Orthogonal frequency-division multiplexing (OFDM) is a method of digital signal modulation in which a single data stream is split across several separate narrowband channels at different frequencies to reduce interference and crosstalk.

➨The original data stream bits -- that in a conventional single-channel modulation scheme would be sent serially (one after the other) -- are transmitted in parallel (several at once on separate channels) but at lower speed in each substream (a stream within another stream) relative to the original signal. 

➨This means symbols sent in the substreams are longer and spaced farther apart. In the original stream, each bit might be represented by a 1-nanosecond (ns) segment of the signal, with 0.25 ns spacing between bits.

➨Splitting the signal across four component streams lets each bit be represented by 4 ns of the signal with 1ns spacing between. This reduces interference among symbols and makes it easier to receive each symbol accurately while maintaining the same throughput.

# OFDMA SPECTRUM

![ofdm-orthogonal-frequency-division-multiplexing-01](https://user-images.githubusercontent.com/25082554/46089335-e4720680-c1cb-11e8-81b0-c9b32cf54ded.gif)

➨OFDM is used in Wi-Fi, DSL internet access, 4G wireless communications, and digital television and radio broadcast services.

➨It is variation of FDM technique in which orthogonal subcarriers are closely spaced to have efficient utilization of bandwidth. 

➨OFDM subcarriers carry different data in parallel simultaneously to achieve high data rate. It is also known as digital multi-carrier modulation scheme. 

![ofdm-transmitter-with-spectrum](https://user-images.githubusercontent.com/25082554/46088582-4893cb00-c1ca-11e8-80f9-ff5fbbeb71d8.jpg)

# Benefits or advantages of OFDM

Following are the benefits or advantages of OFDM:

➨The OFDM spectrum is composed of overlapped narrow subcarriers. This makes efficient usage of frequency spectrum compare to traditional FDM method.

➨In OFDM broadband channel is divided into smaller narrowband subchannels. This makes OFDM resistive to frequency selective fading. Moreover OFDM transmit/receive chain uses channel encoder/decoder and interleaver/deinterlaver which help in recovering lost OFDM symbols due to fading.

➨OFDM makes use of cyclic prefix to eliminate ISI (Inter Symbol Interference) found in the multipath channel environment. Hence it is robust to multipath fading.

➨Channel estimation and equalization has been carried out using known pattern (i.e. preamble) and embedded pilot carriers in a symbol. This is more simpler and efficient compare to channel equalization used in to SC (Single Carrier) system.

➨Time offset estimation and correction algorithms are very easy due to correlation technique.

➨It is possible to allocate bandwidth as per resource requirements. Hence OFDM is bandwidth scalable technique.

###### Drawbacks or disadvantages of OFDM

Following are the disadvantages of OFDM:

➨OFDM signal spectrum has higher PAPR (Peak to Average Power Ratio). Due to this, OFDM based transmission system requires RF PA (Power Amplifier) with higher PAPR.

➨It has higher carrier frequency offset due to different LOs (Local Oscillators) and DFT leakage. This requires complex frequency offset correction algorithms at the OFDM receiver.

➨It is prone to ISI (Inter Symbol Interference) and ICI (Inter Carrier Interference). This requires time offset and frequency offset correction algorithms.

➨As OFDM spectrum travels through multiple paths which require guard band to avoid ISI errors due to timing offsets.

