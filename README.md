# bwtc32key
A better version of BWTC32768 by github user @stgiga (my old account). BWTC32768 was A highly-efficient, fully-handwriteable, legacy-compatible, human-readable, human-speakable, unambiguous, mostly safe, text-armored, and simple UTF16-based binary-to-text file encoder based off tinygma's CJK-only implementation of github user @qntm's Base32768 (by user @kusano_k on https://qiita.com/kusano_k/items/124727ed346a008434c9 (who also goes by @kusano on Github), who put the full implementation on https://tinygma.sweetduet.info), that compresses the input data with github user Elad Karako/@eladkarako's compressjs-flattened's bwtc algorithm (originally written in GNU C by github user @pjkmikkol/Pekka Mikkola (with code and concepts from Julian Seward, Yuta Mori, Peter Fenwick, Juha Karkkainen, Dominik Kempa, and "Elias, Rissanen and Pasco, plus Alistair Moffat, Radford Neal and Ian Witten", Michael Burrows, and David Wheeler) and ported to JS by github user @cscott/C. Scott Ananian as a part of compressjs) that beats bzip and bzip2 by Julian Seward (with the BWT from Michael Burrows and David Wheeler, David Huffman for the Huffman coder, Peter Fenwick for the Arithmetic coder, and "Elias, Rissanen and Pasco, plus Alistair Moffat, Radford Neal and Ian Witten" for the original Arithmetic Coder that Peter Fenwick improved.) on "https://bzip.org". 
BWTC32key has the added security benefit over BWTC32768 of some simple AES-256-CTR security from aes-js by github user @ricmoo, paired with an 8BITASCII-only tiny SHA256 password hasher by github user @geraintluff to fit the resource frugal theme of the compressor and encoding. There are probably many others left to credit for all the code in this web app. Credit goes to them. The app is nicely bundled into a demo here: http://sentogiga.github.io/bwtc32key
