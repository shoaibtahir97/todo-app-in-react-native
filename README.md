Import React Native elements in place of HTML/JSX Elements which are imported from 'react-native' library
<View> === <div>
<Text> === <p>/<h1>

Always place <Text> inside <View>. You cannot use <Text> outside <View>

CSS does not work in React Native as we are not using browser. In order to implement styles we will use styles object of JavaScript