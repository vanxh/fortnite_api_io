# Fortnite

An api wrapper for https://fortniteapi.io in dart.

[![pub.dev Version](https://img.shields.io/pub/v/fortnite_api_io.svg)](https://pub.dev/packages/fortnite_api_io/)
[![Discord Server](https://discord.com/api/guilds/797736897941995540/widget.png)](https://discord.gg/fishstick)

## Installation

Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
    fortnite_api_io: any
```

then run in terminal

```
dart pub get
```

or use your prefferd text editor or IDE to install the plugin.

## Usage Example

```dart
import "package:fortnite_api_io/fortnite_api_io.dart";

void main() async {
  final FortniteApiIo fn = FortniteApiIo(
    apiKey: "YOUR API KEY",
  );

  ChallengeResponse c = await fn.getChallenges();
  print("There are ${c.bundles.length} challenge bundles available.");
}
```

## Links

-   [Discord](https://discord.gg/fishstick)
-   [pub.dev](https://pub.dev/packages/fortnite_api_io/)
-   [Documentation](https://pub.dev/documentation/fortnite_api_io/latest/)

## License

Copyright 2021 Vanxh

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
