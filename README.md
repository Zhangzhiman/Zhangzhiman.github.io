```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        ScrollView {
            VStack {
                Image("https://s2.loli.net/2024/11/30/ZyGfnv3TOpVQqME.jpg")
                    .resizable()
                    .aspectRatio(contentMode: .fit)
                    .frame(width: 1200, height: 675)
                Text("Hello!\nThis is\nmy personal webpage\nWelcome!")
                    .padding()
                Button(action: {
                    // Action for button tap
                }) {
                    VStack {
                        Text("张芷曼")
                    }
                }
                Text("AS a college student currently sstudying, GitHub is a great recommendation as a \"homework assistant\" for computers. Here are some of its main advantages:")
                    .padding()
                VStack(alignment: .leading) {
                    Text("Having a massive number of open source projects")
                    Text("suitable for novice developers to learn.")
                    Text("Writing a comprehensive resume")
                    Text("can be very helpful for job interviews and applications.")
                    Text("Collaborative development")
                    Text("improve team collaboration efficiency.")
                }
                Image("https://s2.loli.net/2024/11/30/ZumPkhtxin7bWUL.jpg")
                    .resizable()
                    .aspectRatio(contentMode: .fit)
                    .frame(width: 810, height: 746)
                Text("Contact me")
                    .font(.title)
                    .padding()
                Image("https://s2.loli.net/2024/11/30/VruAwg9Sa42nTZX.jpg")
                    .resizable()
                    .aspectRatio(contentMode: .fit)
                    .frame(width: 451, height: 549)
                Text("Just give me a call or send us a mail:\n\n202412988@hbmzu.edu.cn\nPhone: 15272238757")
                    .padding()
                Button(action: {
                    // Action for sending email
                }) {
                    VStack {
                        Text("Send e-mail")
                    }
                }
                Button(action: {
                    // Action for calling phone number
                }) {
                    VStack {
                        Text("Call me")
                    }
                }
            }
        }
    }
}

struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
```
