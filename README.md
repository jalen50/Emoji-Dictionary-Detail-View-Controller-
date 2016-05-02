# Emoji-Dictionary-Detail-View-Controller-

//
//  EmojiDetailViewController.swift
//  Emoji Dictionary 2
//
//  Created by Jalen Thompson on 4/1/16.
//  Copyright (c) 2016 Jalen Thompson. All rights reserved.
//

import Foundation
import UIKit

class EmojiDetailViewController : UIViewController {
    
    
    @IBOutlet weak var emojiLabel: UILabel!
    
    @IBOutlet weak var emojiDefinitionLabel: UILabel!
    var emoji = "💀"
    var emojiDefinition = "My Def"
    
    override func viewDidLoad() {
        self.emojiLabel.text = self.emoji
        self.emojiDefinitionLabel.text = self.emojiDefinition
    }
    
}
