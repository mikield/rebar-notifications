# Rebar Notification Plugin

Rebar Notification Plugin is a plugin for the Rebar Framework that allows you to display custom notifications in your application with a que.

## Usage

### Adding a Notification

You can add a notification by calling the `addNotification` method provided by the plugin. Here's an example of how to use it:

# Serverside

```javascript
NotifyController.addNotification(player, {
    icon: '🤑',
    title: 'Some Notification...',
    message: `You've successfully bought x${items} for ${totalPrice}$!`,
    duration: 5000,
});
```

# Clientside

-   Will Follow

# Params

-   `icon`: The emoji to display in the notification.
-   `title`: The title of the notification.
-   `subtitle`: The subtitle of the notification.
-   `message`: The notification message.
-   `duration`: The duration in milliseconds for how long the notification should be displayed.
-   `oggFile?`: Sound (ogg) of the notification from /sounds folder.

# Interface
```javascript
export interface Notification {
    icon: string;
    title: string;
    subTitle: string;
    message: string;
    duration?: number;
    oggFile?: string;
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Getting Started

To get started with the Rebar Notification Plugin, you can clone it from the source code.

1. Clone the repository:

```shell
git clone https://github.com/Booster1212/rebar-notifications
```

## Acknowledgments

-   This project was inspired by the need for a simple and customizable notification system in Rebar applications.

## Authors

-   [Der Lord!](https://github.com/Booster1212)

## Support

For support, bug reports, or feature requests, please create an issue here on GitHub.

## Release History

-   1.0.0
    -   Initial release

## Changelog

See the [CHANGELOG.md](CHANGELOG.md) file for details about changes between versions.
