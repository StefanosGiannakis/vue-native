<template>
    <button
        :on-press="onPressLearnMore"
        title="Learn More"
        color="#841584"
        accessibility-label="Learn more about this purple button"
    />
</template>

<script>
import { Alert } from 'react-native';
export default {
    methods: {
        onPressLearnMore: function() {
            Alert.alert(
                'Vue Js App',
                'Woohoo it works !!!',
                [
                    {text: 'Ask me later', onPress: () => console.log('Ask me later pressed')},
                    {text: 'Cancel', onPress: () => console.log('Cancel Pressed'), style: 'cancel'},
                    {text: 'OK', onPress: () => console.log('OK Pressed')},
                ],
                { cancelable: false }
            );
        }
    }
}
</script>