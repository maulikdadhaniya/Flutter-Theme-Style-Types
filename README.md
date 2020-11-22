# Flutter Theme Basic

<table>
  <tr><td> <b>Deafult Theme Light</b> </td></tr>
  <tr>
    <td>
      <pre>
      MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData.light(),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
      );
      </pre></td><td><img src="https://github.com/maulikdadhaniya/Flutter-Theme-Style-Types/blob/main/assets/defaultlight.jpg" width=200></tr>
 </table>

 <table>
       <tr><td> <b>Deafult Theme Dark</b> </td></tr>
  <tr>
    <td>
      <pre>
      MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData.dark(),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
      );
      </pre></td><td><img src="https://github.com/maulikdadhaniya/Flutter-Theme-Style-Types/blob/main/assets/defaultdark.jpg" width=200></tr>
      </table>

 <table>
       <tr><td> <b>Global Themes</b> </td></tr>
  <tr>
    <td>
      <pre>
      MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(
             primaryColor: Colors.purple[800],
             accentColor: Colors.amber,
             accentColorBrightness: Brightness.dark
            ),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
      );
      </pre></td><td><img src="https://github.com/maulikdadhaniya/Flutter-Theme-Style-Types/blob/main/assets/globaltheme.jpg" width=200></tr>
      </table>

  <table>
       <tr><td> <b>Adapting Themes</b> </td></tr>
  <tr>
    <td>
      <pre>
      MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData.dark().copyWith(
             primaryColor: Colors.purple[800],
             accentColor: Colors.amber,
            ),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
      );
      </pre></td><td><img src="https://github.com/maulikdadhaniya/Flutter-Theme-Style-Types/blob/main/assets/adaptivetheme.jpg" width=200></tr>
      </table>

